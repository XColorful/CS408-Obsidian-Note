```c
int Index_BF(string s, string t) {
	int i = 1, j = 1;
	int lens = s.length();
	int lent = t.length();
	while (i < lens && j < lent) {
		if (s[i] == t[j]) {
			i++, j++;
			continue;
		} else {
			i = i - j + 2; // i指示主串S正在比较的字符位置
			j = 1; // j指示子串t正在比较的字符位置
		}
	}
	if (j == lent) {
		return i - j;
	}
	return -1;
}
```
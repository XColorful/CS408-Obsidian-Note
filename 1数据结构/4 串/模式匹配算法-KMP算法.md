```c
void get_next(String T, int next[]) { //计算next数组
	int i = 1, j = 0;
	next[1] = 0;
	while (i < T.length) {
		if (j == 0 || T.ch[i] == T.ch[j]) {
			++i;
			++j;
			next[i] = j;
		} else {
			j = next[j];
		}
    }
}

int Index_KMP(String S, String T, int next[]) {
	int i = 1, j = 1;
	while (i <= S.length && j <= T.length) { //i永远不递减
		if (j == 0 || S.ch[i] == T.ch[j]) { //字符匹配成功,指针后移
			++i;
			++j;
		} else { //字符匹配失败, 根据next跳过前面的一些字符
			j = next[j];
		}
	}
	if (j > T.length)  // 匹配成功
		return i - T.length;
	else
		return 0;
}
```
```c
// 信号量定义
typedef struct semaphore {
	int value; // 信号量值
	struct pcb * list; // 信号量队列指针
}

// P操作
void P(semaphore s) {
	s.value--;
	if (s.value < 0)
		asleep(s.list);
}

// V操作
void V(semaphore s) {
	s.value++;
	if (s.value <= 0)
		wakeup(s.list);
}
```
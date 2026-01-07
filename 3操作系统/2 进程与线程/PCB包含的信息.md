![[PCB包含的信息.jpg]]

| | |
|---|---|
|<font color="#c0504d">进程描述信息</font>|- <font color="#4f81bd">进程标识符PID</font>：标识各个进程，每个进程都有一个并且唯一的标识符<br>- <font color="#4f81bd">用户标识符UID</font>：进程归属的用户，用户标识符主要为共享和保护服务|
|<font color="#c0504d">进程控制和管理信息</font>|- <font color="#4f81bd">进程当前状态</font>，如 new、ready、running、waiting 或 blocked 等<br>- <font color="#4f81bd">进程优先级</font>：进程抢占 CPU 时的优先级|
|<font color="#c0504d">资源分配清单</font>|- 有关内存地址空间或虚拟地址空间的信息<br>- 所打开文件的列表和所使用的 I/O 设备信息|
|<font color="#c0504d">CPU 相关信息</font>|- <font color="#4f81bd">CPU 中各个寄存器的值</font><br>- 当进程被切换时，CPU 的状态信息都会被保存在相应的 PCB 中以便进程重新执行时，能从断点处继续执行|
- <font color="#c0504d">转移指令</font>时，需要判别转移是否成功，若成功则PC修改为转移指令的目标地址，否则下一条指令的地址仍然为PC自增后的地址
- <font color="#c0504d">计算机分两大部分</font>：<font color="#c0504d">控制部件</font>和<font color="#c0504d">执行部件</font>
	- 控制器就是控制部件，指令寄存器，操作控制器，程序计数器都是控制部件
	- 运算器，存储器，外围设备就是执行部件
- <font color="#c0504d">各寄存器的位数等于什么</font>？【和地址有关的就取决于机器字长，和数据大小有关的就取决于容量】

|<font color="#9bbb59">通用寄存器</font>|<font color="#9bbb59">PC</font>|<font color="#9bbb59">IR</font>|<font color="#9bbb59">MAR</font>|<font color="#9bbb59">MDR</font>|
|---|---|---|---|---|
|机器字长|存储器容量|指令字长|指令字长|机器字长=CPU的位数|
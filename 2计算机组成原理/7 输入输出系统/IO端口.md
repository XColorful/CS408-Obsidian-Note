- <font color="#c0504d">I/O端口</font>：接口电路中可以被CPU直接访问的寄存器，即接口中用于暂存信息的寄存器
- 在执行一条指令时，CPU使用地址总线选择所请求的I/O端口，使用数据总线在CPU寄存器和端口之间传输数据
- I/O端口想要能被CPU访问，则必须对各个端口进行编号，<font color="#c0504d">每个端口对应一个端口地址</font>
- 主要的I/O端口及其功能

|<font color="#c0504d">数据端口</font>|<font color="#c0504d">状态端口</font>|<font color="#c0504d">控制端口</font>|
|---|---|---|
|CPU对数据端口<font color="#c0504d">执行读写操作</font>|对状态端口只能<font color="#c0504d">执行读操作</font>|对控制端口只能<font color="#c0504d">执行写操作</font>|
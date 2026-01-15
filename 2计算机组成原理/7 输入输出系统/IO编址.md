| |<font color="#9bbb59">统一编址</font>（<font color="#9bbb59">存储器映射方式</font>）|<font color="#9bbb59">独立编址</font>（<font color="#9bbb59">I/O映射方式</font>）|
|---|---|---|
|定义|- 把I/O端口当做<font color="#c0504d">存储器的单元进行地址分配</font>，CPU<font color="#c0504d">不需要设置专门的I/O指令</font>，用<font color="#c0504d">统一的访存指令</font>就可以访问I/O端口|- I/O端口的<font color="#c0504d">地址空间与主存地址空间</font>无法从地址码的形式上区分<br>需要设置<font color="#c0504d">专门的I/O指令来访存I/O端口</font>|
|特点|- 依靠地址码的不同区分存储单元和I/O设备|- 通过专门的I/O指令来区分存储单元和I/O设备|
|优点|- 不需要专门的I/O指令<br>- 可以使CPU访问I/O的操作更灵活、更方便<br>- 还可以<font color="#c0504d">使端口有较大的编址空间</font>|- 输入/输出指令与存储器指令有明显区别<br>- 程序编制清晰，便于理解|
|缺点|- 端口占用存储器地址，使<font color="#c0504d">内存容量变小</font><br>- I/O设备进行数据输入/输出操作时，<font color="#c0504d">执行速度较慢</font>|- 输入/输出指令少，<font color="#c0504d">一般只能对端口进行传送操作</font><br>- 尤其需要CPU提供存储器读/写、I/O设备读/写两组控制信号增加了控制的复杂性|
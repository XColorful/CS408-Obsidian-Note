<font color="#9bbb59">用户可见的寄存器</font>
- 可对这类寄存器编程
- <font color="#c0504d">e.g. 通用寄存器、PSW、基址寄存器（用于实现多道程序设计或者编制浮动程序）、状态/标志寄存器</font>

<font color="#9bbb59">用户不可见的寄存器</font>
- 对用户是透明的
- 保留各种状态信息
- 如溢出标志OF，符号标志SF，零标志ZF，进位标志CF
- PSW中的这些位参与并决定微操作的形成
- 不可对这类寄存器编程
- e.g. <font color="#c0504d">MAR、MDR、IR、微程序控制器CM</font>
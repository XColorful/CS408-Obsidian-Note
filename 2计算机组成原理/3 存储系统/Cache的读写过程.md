| | |
|---|---|
|![[Cache的读写过程.jpg]]|<font color="#9bbb59">CPU、Cache、和主存三者的读写关系</font><br>- Cache会从主存中一并读取目标数据以及附近空间的数据【通常以块为单元取出】【速度如图需要1000ns】<br>- CPU要取数据会优先从Cache中读取，因为速度快【速度如图5ns】<br>- CPU计算完后，会把数据再次返回给Cache【速度也是5ns】<br><font color="#9bbb59">如果无法从Cache中直接高速存取，CPU会用两种模式进行补救</font><br>- 赶紧让Cache读取主存，CPU再从Cache中读取。<br>- CPU一边直接访问主存读取，一边让Cache读取主存，CPU再从Cache中读|
- 主存与CPU之间的数据传送也要借助CPU内部总线完成
- <font color="#c0504d">以CPU从主存读取指令为例</font>，实现传送操作的流程的控制信号为

| | |
|---|---|
|PC → Bus → MAR|PCout和MARin有效，现行指令地址 → MAR|
|1 → R|CU发读命令|
|MEN(MAR) → MDR|MDRin有效|
|MDR → Bus → IR|MDRout和IRin有效，现行指令 → IR|
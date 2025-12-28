| | |
|---|---|
|<font color="#8064a2">源端口和目的端口</font>|TCP分用功能的实现|
|<font color="#8064a2">序号</font>|报文段所发送的数据的第一个字节的序号|
|<font color="#8064a2">确认号</font>|期望收到下个报文段第一个数据字节的序号|
|<font color="#8064a2">数据偏移/首部长度</font>|TCP首部的长度|
|<font color="#8064a2">保留</font>|占6位，保留为今后使用|
|<font color="#8064a2">紧急位URG</font>|表明报文段中有紧急数据|
|<font color="#8064a2">确认位ACK</font>|仅当ACK=1确认号才有效|
|<font color="#8064a2">推送位PSH</font>|实际很少使用|
|<font color="#8064a2">复位位RST</font>|TCP连接出现差错，需释放连接重新建立|
|<font color="#8064a2">同步位SYN</font>|在连接建立时用来同步序号|
|<font color="#8064a2">终止位FIN</font>|用来释放一个连接，FIN=1表明报文段的发送方数据已发送完毕，并要求释放运输连接|
|<font color="#8064a2">窗口</font>|作为接收方让发送方设置其发送窗口的依据|
|<font color="#8064a2">校验和</font>|校验首部和数据部分，需要伪首部|
|<font color="#8064a2">紧急指针</font>|URG=1时表示报文段中紧急数据的字节数|
|<font color="#8064a2">选项</font>|最大报文长度MSS：TCP报文段数据部分的长度<br><br>扩大窗口<br><br>时间戳|
|<font color="#8064a2">填充</font>|可变部分|
<font color="#c0504d">快重传</font>
- 当发送方连续收到3个重复的ack报文时，直接重传对方尚未收到的报文段
- 不必等待那个报文段设置的重传计时器超时

<font color="#c0504d">快恢复</font>
- 当发送方连续收到3个冗余ack时，执行“乘法减小”算法
- 把ssthresh设置为当前cwnd的一半，然后cwnd从ssthresh开始使用拥塞避免算法
####若干疑问

1.linux下，如果TCP连接建立后，拔除网线，TCP状态如何？
阻塞和非阻塞，同步和异步

2.TCP连接三次握手，服务端发送SYN/ACK分节回应客户端，如果客户端不会送ACK分节，服务端TCP状态如何？
服务端一段时间未收到客户端的ACK应答，重发几次后认定连接建立失败。

3.TCP终止四次挥手，服务端发送FIN分节，进入LAST_ACK状态，如果收不到客户端的ACK分节，状态如何？

## 数据封装过程
- 数据格式
TCP数据信息：TCP头部＋实际数据（TCP头包括源和目标主机端口号、顺序号、确认号、校验字
等）
IP数据包：IP头部＋TCP数据信息（IP头包括源和目标主机IP地址、类型、生存期等）
数据帧：帧头＋IP数据包＋帧尾（帧头包括源和目标主机MAC初步地址及类型，帧尾是校验字）

- 数据的封装与解封装
封装：数据要通过网络进行传输，要从高层一层一层的向下传送，如果一个主机要传送数据到
别的主机，先把数据装到一个特殊协议报头中，这个过程叫－－－－－封装。
解封装：上述的逆向过程

- 当数据以TCP/IP协议传输时的封装与街封装过程如下图：
![pic](https://m.qpic.cn/psc?/V53fQItE1IbEAS1mwOTY1xSqBj2RqS6f/ruAMsa53pVQWN7FLK88i5uSDOhGZk*jmNvrKqQjnGpsODFSDpa9XdZ0jTZFQojrCPxU4oQBrUSVH*PJ5P4YfCTdho6ZYG7M3mOScr*9O6Zc!/mnull&bo=7QLdAQAAAAADBxE!&rf=photolist&t=5)
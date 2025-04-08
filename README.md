# HotRAT 4.1
 HotRAT 4.1
一款用于批量控制PC的系统
由 WebAPI服务器、套接字服务器、主控端、被控端组成

### 原理：
- 将服务端部署到云服务器或本地设备，被控端连接到套接字服务端。
- 套接字服务端同步数据到WebAPI服务端，用户再创建会话从服务端中转并与被控端进行连接。

### 优势：
- 1.完全通过API来连接到被控端，所以可以用任何语言在任何平台构建主控端。
- 2.使用.Net8.0，可以部署到Windows、Linux、MacOS甚至运行有终端工具的Android设备。
- 3.使用加密算法验证临时Token，防止恶意劫持。


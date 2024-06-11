# Socket_chat
基于Socket的聊天室_java聊天室
**一、系统主要功能如下：**
Java程序分为服务器端和客户端两部分：

服务器端功能：

1、启动时首先读入一个用户文件，用户文件中保存的是全部用户（至少10个）的用户名及密码（明文保存，真实系统不会明文保存的）。然后显示一个提示符，等待输入命令。可接受的命令包括list：列出全部在线用户；listall：列出全部用户；quit：退出系统；

2、在固定端口（8000以上）侦听，等待客户端连接；

3、客户端连接成功后有一个验证用户名和密码的过程。如果用户名密码正确，要给该客户端发成功验证的提示信息，否则给客户端发送用户名或密码错误信息，并等待用户再次验证，直到验证成功或客户端断开；

4、至少支持5个客户端同时聊天；

5、转发客户端发送的聊天信息；

5、转发客户端发送的聊天信息；

6、日志功能，记录每个用户的登录、退出登录的时间和IP地址（要求用读写文件的形式实现）。

客户端功能要求：

1、启动后首先要连接到服务器端；

2、连接成功后提示用户输入用户名及密码，并将用户输入的用户名及密码发给服务器端验证。

验证成功后则成功进入聊天室，否则提示用户重新输入用户名及密码，直到验证成功或用户结束程序；

3、验证成功后进入聊天室，聊天室要有提示符；4、聊天室内要能显示所有用户的聊天信息；

5、在聊天室内用户可以输入两类字符串：①普通字符串，为广播类聊天信息，所有人都可以看到；②@+命令，为系统命令；

6、系统命令有：list：列出当前在线用户；

quit：退出系统。



**二、系统截图**
1、服务端

![image.png](http://124.222.106.130:8081/api/resource/getFile?name=articlePicture/Sara11713087621360161.png)

2、用户（张三）

![image.png](http://124.222.106.130:8081/api/resource/getFile?name=articlePicture/Sara11713087642913375.png)

3、用户李四

![image.png](http://124.222.106.130:8081/api/resource/getFile?name=articlePicture/Sara11713087682352999.png)



1、服务端
系统描述及截图

http://124.222.106.130:8081/xiaoyu/#/article/2

三、操作说明

直接使用Idea打开，然后将【user.txt】放到D盘根目录下。如果需要放在其他地方，修改server.java文件里面的uerPath即可

源码下载地址：http://124.222.106.130:8081/xiaoyu/#/article/2

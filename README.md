# AudioQueue
1、录制的音频编码格式是aac_ld

2、使用AudioQueue进行播放和录制

3、项目是根据苹果官方demo-SpeakHere改制而成

4、传输使用的是TCP协议

5、为了测试实时传输，我写了一个简单的服务器程序TestSV是服务器项目，做测试需要先启动TestSV项目，修改里面监听的ip和端口为你电脑的本
地ip,然后通过macox运行项目，项目运行起来后会有监听成功的log。

6、确保你的手机和电脑在同一个局域网内，启动RealTimeTransport
iPhone端项目，修改里面服务器地址和端口，同服务器端的一致,然后在iphone手机上运行项目，这时候自己说话自己就可以听到了。

7、客户端程序需要真机运行！否则无法录制音频。

copyright @ Hero.
如有问题
联系方式：cx12080605@163.com

# sofe-and-hard
《软硬结合——写给硬件开发工程师的全栈入门实战》，软硬件结合可以说是所有硬件开发人员心中的一大追求，当一个人技能树上点亮了软硬件，所有创意想法基本都能靠自己去实现。

## 起源
2017年毕业时做的毕业设计是一个物联网项目，硬件上是STM32+ESP8266，自己搭服务器（nodejs+mongodb），客户端做网站做微信小程序（我觉得我是第一个用微信小程序做毕设的人），打算将这个项目重构并写出教程，针对硬件开发人员写的全栈应用开发入门实战。2018年开始写这教程时，我的水平是不足一年工作经难的初级全栈工程师+ 略懂硬件开发。

## 如何开始
1. 百度git 并运行安装
![百度git 并运行安装示意图](http://ww1.sinaimg.cn/large/005BIQVbgy1fqtnovsgrmj31hc0qdjxv.jpg)
2. 在桌面上右键点击 `git bash Here`
3. `git clone https://github.com/alwxkxk/sofe-and-hard.git`
4. 可以看到下载了一个文件夹，进去点击`第一次阅读.html`
5. 整个教程在不断更新中，进入文件并运行`git pull`即可更新。
![git clone示意](http://ww1.sinaimg.cn/large/005BIQVbgy1fqtnqg91l9g31h30rmu0z.gif)
6. 之后就进入到Part1 点击`index.html`正式开始阅读。
## 教程特点
- 整个项目部署运行傻瓜式地教，保证整个项目能在读者手上运行起来。
- 尽可能地解答会卡住大家继续项目走下去的所有问题。
- 整个项目能在读者手上运行起来只是鱼，我还会授渔，在教程里会着重详解遇到问题我是怎么解决问题的。
- 我不生产水，我只是水的搬运工，别人已经写好的教程不再重复写，比如HTML的学习，nodejs的学习,linux学习等等，都会告诉你们怎么利用网络搜索需要自学的教程，此教程做的只是连珠成串。
## 教程目录 与 安排
### Part1
整个项目介绍并让大家先简单地运行起来~ 包含ESP8622烧录固件，各环节自调与联调。
- 前提：有一定硬件调试经验（USART串口调试，AT指令）
- 成果：把Part1 的demo运行起来，实现本地WIFI下手机监控硬件。
- 关键词：STM32、串口调试、AT指令、ESP8266、git、网络调试助手
- 耗时：估计5到8小时
### Part2
讲解Part1 demo，包含静态网页制作，express框架。
- 成果：简单的网页开发与Nodejs应该能入门了，有能力修改出自己想要的页面效果。
- 关键词：HTML、Javascript、CSS、Jquery、bootstrap、w3cschool、菜鸟教程、《深入浅出nodejs》、《七天学会NodeJS》、TCP服务器、express
- 耗时：自学网页开发（估计5到8天），自学nodejs（估计5到10天），共估计10到20天差不多能入个门。__1天按8到12个小时来计算（超高强度），下面同理__
### Part3
将Part1 demo运行在云服务器上，主要是学习linux（ubuntu），云服务器各种折腾。
- 成果：Linux初步入门、部署到云服务器上，此时真正实现远程监控硬件。
- 关键词：ubuntu、云服务器、vi、《鳥哥的 Linux 私房菜》、bash、Xshell、winSCP
- 耗时：自学linux估计5到10天左右能入个门。
### Part4
引入mongoDB数据库，将数据保存到数据库里，并将历史数据可视化。  
（可选学）并讲一些协议，包含TCP协议(讲一下基于TCP自定义自己的协议规则)，HTTP协议，websocket协议。然后会进行优化，如把HTTP轮询换成websocket协议。
- 成果：完成Part4 demo，数据可视化会让整个效果更炫，增加实时性，这个物联网项目基本成型。
- 关键词：《计算机网络》、tcpdump、wireshark、《TCP/IP详解》、socketio库、echart库、TLV格式
- 耗时：数据可视化几个小时入个门，数据库估计2天入门，协议简单地点一下1天，要想跟着继续深入可能要多花几天。整个可能需要5到10天吧。
### Part5
Part5及往后看阅读情况写吧。
各种性能测试与优化，ESP8266的AT固件改成自己编译的固件（这个蛮难搞的），说一下各物联网平台。
- 关键词：redis、nginx、CDN
### Part6
使用electron开发PC桌面软件，使用ionic开发手机APP。
- 关键词：electron、ionic
## 声明
保留一切权利，禁止商业转载，非商业转载时必须保留此声明与网址：https://github.com/alwxkxk/sofe-and-hard。



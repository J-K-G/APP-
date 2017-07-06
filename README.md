
# APP服务端搭建
1、Tomcat的下载安装：

官网下载：http://tomcat.apache.org/download-90.cgi

安装：下载到本地后直接加压即可。

启动：到bin目录下，双击startup.bat。

![iamge text](https://github.com/J-K-G/APP-/blob/master/image/tomcat_bin.png) 

打开后可以看到如下窗口信息

![iamge text](https://github.com/J-K-G/APP-/blob/master/image/tomcat_open.PNG) 

调试：到浏览器上输入localhost:8080，如果能看到tom猫就说明成功了。

![iamge text](https://github.com/J-K-G/APP-/blob/master/image/tomcat_test.PNG)

注意：前提是要安装配置了jdk！



2、MySQL下载和安装：

官网下载：https://dev.mysql.com/downloads/file/?id=469273 （点击页面后的No,thanks...可以直接下载）

版本5.7.17直接傻瓜式安装，然后配置环境变量，在path中添加server的bin目录
C:\Program Files\MySQL\MySQL Server 5.7\bin

测试是否安装成功：
cmd --> mysql -u root -p ，然后输入密码就可以看到对应信息

![iamge text](https://github.com/J-K-G/APP-/blob/master/image/mysql_test.PNG)

MySQL安装博客（win10）：http://blog.csdn.net/vincentlmeng/article/details/70160475

MySQL安装博客：http://blog.csdn.net/youyu_torch/article/details/74512946

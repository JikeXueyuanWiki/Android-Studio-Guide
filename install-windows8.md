# Android Studio安装（Win8）

## 下载地址

http://developer.android.com/sdk/installing/studio.html

## 在 Win 8 上安装Android Studio

### 安装jdk

必须安装JDK1.7 ,1.6运行不了

### 配置环境变量

在环境变量（计算机=》右键=》高级系统设置）里面添加ANDROID_STUDIO_JDK ，

值为JDK位置：C:\Program Files\Java\jdk1.7.0_21，

添加JAVA_HOME，值：C:\Program Files\Java\jdk1.7.0_21;，

在PATH内添加：;%JAVA_HOME%\bin;%JAVA_HOME%\jre\bin;C:\Program Files\Java\jdk1.7.0_21\bin;D:\android-studio\sdk\platform-tools;，

添加CLASSPATH，值.;%JAVA_HOME%\lib;%JAVA_HOME%\lib\tools.jar

（唉！，java每次都要搞那么多，都什么年代了，添加完成后重启一次计算机，运行cmd，输入java 回车,输入javac 回车；输入 adb 回车，检测是否设置正确）

### 运行
运行android-studio\studio.exe，如果有问题可以测试运行android-studio\bin\studio.bat 看错误信息

运行studio.exe 点调试或者运行报"adb.exe"无法启动时候,可以用运行cmd然后输入"netstat -aon"查看是否有别的程序占用了5307端口,我的机器是wandoujia_adb.exe（豌豆荚） 占用,结束进程自己又启动,无法只有卸载 。

编辑器风格可以在File-》Setting-》Editor-》Colors &Font 里面，选择Darcula就是黑色风格了。不过字体大小好像不可以换。 

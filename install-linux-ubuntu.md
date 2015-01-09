# Android Studio安装（ubuntu）

## 下载安装Android Studio包

cd /home/hxddh/
tar xzvf android-studio-bundle-135.1078000-linux.tgz

## 安装openjdk

cd /
sudo apt-get install openjdk-7-jdk

## 检查java版本

java -version

java version "1.7.0_55"
OpenJDK Runtime Environment (IcedTea 2.4.7) (7u55-2.4.7-1ubuntu1)
OpenJDK Server VM (build 24.51-b03, mixed mode)

## 匹配相关项

cd /etc
sudo vi environment

然后行末Add如下：
JAVA_HOME=/usr/lib/jvm/java-7-openjdk-i386

## 启动配置Android Studio

cd /home/hxddh/android-studio/bin/
./studio.sh

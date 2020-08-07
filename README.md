# mysqlclient_builds
mysqlclient静态编译包，不依赖mysql库，快速安装。包含 Mac、windows、Linux平台。
## 1.简介
python3中操作数据库主要是通过mysqlclient， 可是安装过程比较坑，
(尤其是mac、win平台，主要是会报很多编译的错误，缺少mysql库  缺少编译环境等)
处理起来费事费力。 
本项目提供了 mac  linux win平台的静态编译包。 安装过程无需编译，即安即用。

## 2. 如何使用
#### 1.下载预编译包
根据自己的系统选择适合自己的预编译包。
-  mac系统对应build_macos
-  linux系统对应build_linux
-  windows对应build_windows
比如，对于使用64位python3.7的win用户可下载
mysqlclient-1.4.6-cp37-cp37m-win_amd64.whl

#### 2. 安装
直接通过pip 安装下载好的包。
如:
```shell script
pip3 install mysqlclient-1.4.6-cp37-cp37m-win_amd64.whl
```

## 3. 说明
build_windows中的资源主要来自于 
[加州大学python库](https://www.lfd.uci.edu/~gohlke/pythonlibs/)  
这个站提供了大量win平台的预编译包。

build_macos中是本人根据macos14系统进行编译的，暂未进行大量测试。

build_linux是在centos7系统上进行编译的，已在生产环境进行了小规模验证






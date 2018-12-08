
H5测试页面本地部署
==========================


### 1、安装node

你可以通过以下两种方式在 Mac OS 上来安装 node：

1、在[官方下载网站](https://nodejs.org/en/download/)下载 pkg 安装包，直接点击安装即可。

2、使用 brew 命令来安装：

其他平台请[点击此处](https://www.runoob.com/nodejs/nodejs-install-setup.html)
### 2、npm源替换为淘宝镜像
网络环境好可直接进行第三步

npm config set registry http://registry.npm.taobao.org/

### 3、安装依赖包

1、打开node-server文件夹所在终端

2、安装依赖 npm i

### 4、启动项目

1、启动服务 node server.js

2、浏览器打开 http://localhost:8000

NOTE：手机调试时需要手机和mac连接另一台电脑分享的网络，且此时浏览器打开的网址变为

http://mac的ip地址:8000





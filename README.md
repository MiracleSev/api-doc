## 文档概述
gitbook:基于 Markdown 编写的接口文档；文档中列出几个案例供参考。

## 环境部署/安装
本文档在 gitbook 下运行的，安装步骤如下：
### 1. 克隆源代码
    > git clone https://github.com/MiracleSev/api-doc.git
### 2. 配置本地运行环境
1). 安装 NPM
```shell
sudo apt install npm
sudo npm install n -g 
```
安装长期支持版
```shell
sudo n lts 
```
2). 安装gitbook
```shell
npm install gitbook-cli -g
```
如果安装太慢，可以设置淘宝代理镜像，执行命令：
```shell
npm config set registry https://registry.npm.taobao.or
```
查看gitbook是否安装成功：
```shell
gitbook -V
```
## 使用
进入api-doc目录，执行命令：
```shell
gitbook serve
```
浏览器打开：http://localhost:4000/
即可访问文档。

    

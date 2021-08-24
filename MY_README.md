# Linux ssr 

使用electron-ssr

下载地址：

> https://github.com/qingshuisiyuan/electron-ssr-backup/releases/download/v0.2.6/electron-ssr-0.2.6.deb

安装依赖：

```
sudo apt install libcanberra-gtk-module libcanberra-gtk3-module gconf2 gconf-service libappindicator1·
sudo apt-get install libssl-dev 
sudo apt-get install libsodium-dev
```
开始安装：

```
cd Downloads
sudo dpkg -i *.deb
```

运行软件：

```
electron-ssr
```
运行软件需要python，若没有则`sudo apt install python`

在服务器->订阅管理中添加订阅地址

再更改网络设置中的系统代理如下：

```
代理类型：手动
HTTP代理：127.0.0.1
端口：12333
HTTPS代理：127.0.0.1
端口：12333
```

参考：

> https://www.jianshu.com/p/d64f3a4efcf6
> 
> https://cloud.tencent.com/developer/article/1583099





# psub
利用CF Worker搭建的反代订阅转换工具，通过随机化服务器地址和节点账号密码，解决用户转换订阅的隐私问题

### 演示网站
https://sub.axz.me

### 

环境变量名：`BACKEND`

eg:

https://id9.cc/

`BACKEND`=`https://sub.id9.cc`

`BACKEND`=`https://v.id9.cc`

KV或R2变量名：`SUB_BUCKET`

### 支持反代转换的协议
 - shadowsocks
 - shadowsocksR
 - vmess
 - trojan
 - vless(v0.8.2 Meta后端)
 - hysteria(v0.8.2 Meta后端)

### 视频教程
https://youtu.be/X7CC5jrgazo
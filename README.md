# linux-net-mirror

#### 介绍
网口镜像,阿里云、腾讯云、移动云...其它云.服务器(限制linux)网口数据镜像到另一台服务器

#### 软件架构
软件架构说明

![输入图片说明](https://images.gitee.com/uploads/images/2020/0830/205015_8540ae9d_500345.png "mirror.png")
#### 安装教程
yum install gcc automake make kernel-devel -y
make



#### 使用说明

rmmod pf_ring
insmod pf_ring.ko
./adddev eth0 eth1 52:54:00:94:41:ab 0 
eth0:被镜像口
eth1:镜像数据出口
52:54:00:94:41:ab   ： 数据接收主机mac 需要换成自己的主机的mac
#### 加军魂微信，代码为收费代码,费用500
![加军魂微信](https://images.gitee.com/uploads/images/2020/0830/210033_c0a20278_500345.jpeg "junhun.jpg")

#####付款
![微信支付](https://images.gitee.com/uploads/images/2020/0830/210901_3429dba3_500345.jpeg "weixin.jpg")


![支付宝支付](https://images.gitee.com/uploads/images/2020/0830/210919_92588f0d_500345.jpeg "zhifubao.jpg")




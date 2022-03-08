## alist-koyeb

获取一个Koyeb账号

### 创建

创建`APP`，选择Docker部署，Docker image填写：`docker.io/xhofe/alist:latest`

`Ports`选项的`Port`填写`5244`

`Environment variables`选项的`Value`填写`5244`

![](https://i0.hdslb.com/bfs/album/2b4e96a23c76a56cf9ec5027052cdba0222c92cf.png)

App名称 自定义

其余东西不需要动

### 密码

找到部署记录

![](https://i0.hdslb.com/bfs/album/ad2f6f12e58bd65535ae85734a839ecd7478435c.png)

查看logs

![](https://i0.hdslb.com/bfs/album/e4810ce4156d66edb4e2d5cadc55b4391de8a68d.png)

便可找到密码

### 配置

在CONSOLE选项可自行修改配置，例如修改数据库

![](https://i0.hdslb.com/bfs/album/7972c4a48b26078e97f1fc2e073a080186e8f355.png)

### 使用免费 MySQL 远程数据库

注册免费 MySQL 远程数据库：https://www.db4free.net/

完成注册后，你的邮箱会收到MySQL 连接地址、端口、数据库名称、用户信息

利用CONSOLE即可连接完成

# day4

## 1. 更新source.list,安装mysql
   ### 1. sudo vim /etc/apt/sources.list  --打开source.list删除mouse行
   ### 2. vim .vimrc
   ### 3. 粘贴要更新的源码，覆盖source.list原有内容
    deb http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
    deb http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
    deb http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
    deb http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
     ##测试版源
      deb http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse

    deb-src http://mirrors.aliyun.com/ubuntu/ xenial main restricted universe multiverse
   deb-src http://mirrors.aliyun.com/ubuntu/ xenial-security main restricted universe multiverse
   deb-src http://mirrors.aliyun.com/ubuntu/ xenial-updates main restricted universe multiverse
  deb-src http://mirrors.aliyun.com/ubuntu/ xenial-backports main restricted universe multiverse
   ##测试版源
   deb-src http://mirrors.aliyun.com/ubuntu/ xenial-proposed main restricted universe multiverse

   deb http://archive.canonical.com/ubuntu/ xenial partner
  deb http://extras.ubuntu.com/ubuntu/ xenial main
     ### 4.安装apcth
     sudo apt-get update
     sudo apt-get install tasksel
     sudo tasksel
## 2. 数据库连接本地服务器
     mysql -u root -p
## 3. 运用mysql创建数据库，表
create database stu；

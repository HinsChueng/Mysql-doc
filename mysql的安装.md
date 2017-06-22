# day4

## 1. 更新source.list,安装mysql
      1. sudo vim /etc/apt/sources.list,打开source.list删除mouse行  
      2. vim .vimrc  
      3. 粘贴要更新的源码，覆盖source.list原有内容，安装aptch  
      
## 2. 数据库连接本地服务器
      mysql -u root -p
     
## 3. 运用mysql创建数据库，表
      create database stu；

## 4. Apache安装
      sudo apt-get update
      sudo apt-get install tasksel
      sudo tasksel
## 5. workbench 安装

      sudo apt-get install mysql-workbench

## 6. MySQL 命令行操作
      连接Mysql 格式： mysql -h 主机地址 -u用户名 －p用户密码

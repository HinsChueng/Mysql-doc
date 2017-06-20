# day4

## 1. 更新source.list,安装mysql
      1. sudo vim /etc/apt/sources.list,打开source.list删除mouse行  
      2. vim .vimrc  
      3. 粘贴要更新的源码，覆盖source.list原有内容，安装aptch   
## 2. 数据库连接本地服务器

      mysql -u root -p
     
## 3. 运用mysql创建数据库，表

      create database stu；

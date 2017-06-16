# MySql-doc
## 数据库
 **MySQL简介**    
 MySQL是一个关系型数据库管理系统，由瑞典MySQL AB 公司开发，目前属于 Oracle 旗下产品。  
 MySQL所使用的 SQL 语言是用于访问数据库的最常用标准化语言。  
 MySQL 由于其体积小、速度快、总体拥有成本低，尤其是开放源码这一特点，一般中小型网站的开发都选择 MySQL 作为网站数据库。

 **安装MySQL**  
  `sudo apt-get update` 更新源  
  `sudo apt-get install mysql-client` mysql-server 安装  
  `sudo /etc/init.d/mysqld start` 启动mysql服务  
  **Apache安装**  
  `sudo apt-get update`  
  `sudo apt-get install tasksel`  
  `sudo tasksel`
  **创建所需数据库**
  `create database `<数据库名>
  **使用数据库**  
  `use` <数据库名> 

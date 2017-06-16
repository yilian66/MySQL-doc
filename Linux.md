# MySql-doc
## day1

 **Linux虚拟机创建**  
 一个典型的Linux操作系统组成为：Linux内核，一些GNU程序库和工具,命令行shell，图形界面的X Window系统和相应的桌面环境，
 Shell俗称壳（用来区别于核），是指“提供使用者使用界面”的软件（命令解析器）。
 
 **Linux文件系统介绍**
 *文件系统是操作系统用于明确存储设备或分区上的文件的方法和数据结构；即在存储设备上组织文件的方法。
 
 **Linux基本的文件操作**
 *文件的创建、删除、复制、重命名、移动  
 *列出文件列表
 *查看文件内容
 
 **安装vim，git，更新源**
 

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

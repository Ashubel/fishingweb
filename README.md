﻿# fishingweb

钓鱼网站服务器配合sendMessage使用,前端使用react开发，后端采用flask，最开始用的django，项目小

bundle.js    36800行左右需修改为自己网站url
kami.js 31850行左右修改为自己网站的url

库直接使用diaoyu文件夹下的requirements,pyqt5,mysqlclient请手动安装

安装mysql  创建rxjh数据库   创建rxjhapp_user数据库表
create database rxjh;
create table rxjhapp_user (id int(11) primary key auto_increment,username varchar(25) not null,password varchar(25) not null)engine=InnoDB default=utf8;
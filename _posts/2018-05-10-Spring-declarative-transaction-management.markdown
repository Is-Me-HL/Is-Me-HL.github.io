---
layout: post
title: Spring declarative transaction management
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
tags: [Spring] # add tag
---
### Spring声明式事务管理(注解方式)：
#### 第一步：配置事务管理器
![SpringTxanno1](/assets/img/180510/SpringTxanno1.JPG)
#### 第二步：配置事务注解
![SpringTxanno2](/assets/img/180510/SpringTxanno2.JPG)
#### 第三步：要在使用事务的方法所在类上面添加注解
![SpringTxanno3](/assets/img/180510/SpringTxanno3.JPG)

### Spring声明式事务管理(配置文件方式)：
#### 第一步：配置事务管理器
![SpringTxanno1](/assets/img/180510/SpringTxanno1.JPG)
#### 第二步：配置事务增强
![SpringTx1](/assets/img/180510/SpringTx1.JPG)
#### 第三步：配置切面
![SpringTx2](/assets/img/180510/SpringTx2.JPG)

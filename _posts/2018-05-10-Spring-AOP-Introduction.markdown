---
layout: post
title: Spring AOP Introduction
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: picture3.jpg # Add image post (optional)
tags: [Spring] # add tag
---
#### Spring AOP Introduction

---
##### Aspect oriented programming (AOP)：Enhance one or some of the methods in a class without modifying the source code.

---
##### 1、Configuring AOP in the form of a configuration file
###### 1.1、Two new classes, one for enhancement, and one for enhancement.
![AOP1](/assets/img/180510/AOP1.PNG)

![AOP2](/assets/img/180510/AOP2.PNG)
###### 1.2、In the SRC directory, create a new ApplicationContext.xml file, configure pointcuts and sections.
![AOP3](/assets/img/180510/AOP3.PNG)
###### 1.3、Writing test file test
![AOP4](/assets/img/180510/AOP4.PNG)

![AOP5](/assets/img/180510/AOP5.PNG)
###### This method is demonstrated by front-end enhancement, in addition to post enhancement, surround enhancement and so on.

---
##### 2、Implementation of AOP in the form of annotation
###### 2.1、Two new classes, one for enhancement, and one for enhancement.
![AOP1](/assets/img/180510/AOP1.PNG)

![AOP6](/assets/img/180510/AOP6.PNG)
###### 2.2、In the SRC directory, create a new ApplicationContext.xml file and turn on AOP.
![AOP7](/assets/img/180510/AOP7.PNG)
###### 2.3、Writing test file test
![AOP4](/assets/img/180510/AOP4.PNG)

![AOP5](/assets/img/180510/AOP5.PNG)
###### This method is demonstrated by front-end enhancement, in addition to post enhancement, surround enhancement and so on.

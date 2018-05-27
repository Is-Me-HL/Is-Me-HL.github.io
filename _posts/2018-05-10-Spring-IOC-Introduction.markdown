---
layout: post
title: Spring IOC Introduction
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: picture1.jpg # Add image post (optional)
tags: [Spring] # add tag
---

---

### Introduction
##### Before contacting the framework, most of the time an object is created through the keyword new.But in Spring, we have a simpler and more efficient way to create an object through configuration files or annotations.

---

#### IOC Configuration file creation object：
##### 1、Importing the basic jar package
![SpringIOC1](/assets/img/180510/A.png)
##### 2、Create entity classes
![SpringFile1](/assets/img/180510/SpringFile1.PNG)
##### 3、Create a ApplicationContext.xml file in the SRC directory
![SpringFile](/assets/img/180510/SpringFile.PNG)
##### 4、Writing test file test
![SpringPicture](/assets/img/180510/SpringPicture.PNG)
##### If the test file prints IOC... It indicates that the object was created successfully.

---
#### IOC Create objects by annotation：
##### 1、Importing the basic jar package
![SpringIOC2](/assets/img/180510/SpringIOC2.png)
##### 2、Create entity classes
![SpringAnno2](/assets/img/180510/SpringAnno2.PNG)
##### 3、Create a ApplicationContext.xml file in the SRC directory
![SpringAnno3](/assets/img/180510/SpringAnno3.PNG)
##### 4、Test same
![SpringPicture](/assets/img/180510/SpringPicture.PNG)
##### User objects can also be created through these methods. This is the two basic way for IOC to create objects.

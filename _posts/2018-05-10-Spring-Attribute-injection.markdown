---
layout: post
title: Spring Attribute injection
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: software.jpg # Add image post (optional)
tags: [Spring] # add tag
---

#### Spring Attribute injection
##### Use the set method to inject arrays, map, list and properties attributes into objects.
##### 1、Create an object, and take the set method of each attribute
![ZhuRu1](/assets/img/180510/ZhuRu1.PNG)
##### 2、Create a ApplicationContext.xml file in the SRC directory
![ZhuRu2](/assets/img/180510/ZhuRu2.PNG)
##### 3、Write the test method and get the injection data
![ZhuRu3](/assets/img/180510/ZhuRu3.PNG)

![ZhuRu4](/assets/img/180510/ZhuRu4.PNG)

---
##### If the same attribute is an object, it can still be injected using the set method.
![ZhuRu5](/assets/img/180510/ZhuRu5.PNG)
##### If the entity class has a parameter construction method, it can also use this method to inject attributes. The reference example is as follows.
![ZhuRu6](/assets/img/180510/ZhuRu6.PNG)

---
##### Similarly, with configuration file injection, Spring also provides annotations for injection.
![ZhuRu7](/assets/img/180510/ZhuRu7.PNG)

![ZhuRu8](/assets/img/180510/ZhuRu8.PNG)

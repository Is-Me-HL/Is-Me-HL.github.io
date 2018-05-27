---
layout: post
title: Spring transaction management
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: picture2.jpg # Add image post (optional)
tags: [Spring] # add tag
---
### Spring declarative transaction management(Annotation)：
#### First step: configuration transaction manager
![SpringTxanno1](/assets/img/180510/SpringTxanno1.JPG)
#### Second step: configure transaction annotation
![SpringTxanno2](/assets/img/180510/SpringTxanno2.JPG)
#### The third step: add annotations to the class where the transaction is used.
![SpringTxanno3](/assets/img/180510/SpringTxanno3.JPG)

### Spring declarative transaction management(Configuration file)：
#### First step: configure transaction manager
![SpringTxanno1](/assets/img/180510/SpringTxanno1.JPG)
#### Second step: configure transaction enhancement
![SpringTx1](/assets/img/180510/SpringTx1.JPG)
#### Third step: configure Aspect
![SpringTx2](/assets/img/180510/SpringTx2.JPG)

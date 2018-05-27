---
layout: post
title: SpringIOC Introduction
date: 2018-05-10 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
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

```
package h.l.IOC;

public class User {
	//测试方法
	public void test() {
		System.out.println("IOC...");
	}
}
```
##### 3、Create a ApplicationContext.xml file in the SRC directory

```
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xsi:schemaLocation="
        http://www.springframework.org/schema/beans http://www.springframework.org/schema/beans/spring-beans.xsd">

    <!--创建User对象 -->
    <bean id="user" class="h.l.IOC.User"></bean>
</beans>
```
##### 4、Writing test file test

```
package h.l.IOC;

import org.junit.Test;
import org.springframework.context.ApplicationContext;
import org.springframework.context.support.ClassPathXmlApplicationContext;

public class UserTest {
	@Test
	public void userTest(){
		ApplicationContext context=new ClassPathXmlApplicationContext("ApplicationContext.xml");
		User user=(User)context.getBean("user");
		user.test();
	}
}
```
##### If the test file prints IOC... It indicates that the object was created successfully.

---
#### IOC Create objects by annotation：
##### 1、Importing the basic jar package
![SpringIOC2](/assets/img/180510/SpringIOC2.png)
##### 2、Create entity classes

```
package h.l.IOC;

import org.springframework.stereotype.Component;

@Component(value="user")
public class User {
	//测试方法
	public void test() {
		System.out.println("IOC...");
	}
}
```
##### 3、Create a ApplicationContext.xml file in the SRC directory

```
<?xml version="1.0" encoding="UTF-8"?>
<beans xmlns="http://www.springframework.org/schema/beans"
    xmlns:xsi="http://www.w3.org/2001/XMLSchema-instance"
    xmlns:context="http://www.springframework.org/schema/context" xsi:schemaLocation="
        http://www.springframework.org/schema/beans http://www.springframework.org/schema/beans/spring-beans.xsd
        http://www.springframework.org/schema/context http://www.springframework.org/schema/context/spring-context.xsd"> <!-- bean definitions here -->
    <!-- 开启注解 扫描-->
    <context:component-scan base-package="h.l.IOC"></context:component-scan>
</beans>
```
##### 4、Test same
##### User objects can also be created through these methods. This is the two basic way for IOC to create objects.

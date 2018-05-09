---
layout: post
title: How To Import javaWeb Project
date: 2018-05-08 00:00:00 +0300
description: You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. # Add post description (optional)
img: how-to-start.jpg # Add image post (optional)
tags: [Programming, Learn] # add tag
---
In the process of learning javaWeb and related B/S project development, we may need to import other people's projects into their own eclipse, but there are some problems on the way to the project, which will make the novice get out of the mind, even fear or weary of the project development, the excellent project framework of others. So as a beginner who is learning javaWeb, talk about the solution of the related import project in javaWeb, record it in the following, for the future and the needs of the students a reference, if there is a wrong place, also ask students, seniors do not hesitate to teach.

* step one

Open eclipse->File->Import->General->Existing Projects into Workspace->Browse->Select your project->finish
* step two

Click on the project name, right-click it, and then click properties.

![first](/assets/img/180508/first.PNG)
![second](/assets/img/180508/second.PNG)
![third](/assets/img/180508/thrid.png)
![fourth](/assets/img/180508/thrid.PNG)

* step three

Delete files with unbound identifier and import files corresponding to their own version.

![fiveth](/assets/img/180508/fiveth.PNG)
![sixth](/assets/img/180508/sixth.PNG)
![seventh](/assets/img/180508/seventh.PNG)

Now, a project is imported. But attention is, the above is only the server is different, to do the corresponding modification, may also be different JRE and so on, the same need to repeat the above steps to make corresponding changes. Just skip over here.But, after the corresponding modification. There will be some special problems. For example, the files in project are not wrong, but there will be a small red fork or a red exclamation mark on the document. The following is the perfect solution for my meeting, which is recorded below for your reference.

*About red fork：*

When the eclipse is basically well configured.You need to check the settings folder in the project directory.

![eighth](/assets/img/180508/eighth.png)
![ninth](/assets/img/180508/ninth.png)
![tenth](/assets/img/180508/tenth.png)


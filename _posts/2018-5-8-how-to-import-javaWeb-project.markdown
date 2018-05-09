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

![afirst](/assets/img/180508/first.PNG)
![asecond](/assets/img/180508/second.PNG)
![athird](/assets/img/180508/thrid.png)
![afourth](/assets/img/180508/thrid.PNG)

* step three

Delete files with unbound identifier and import files corresponding to their own version.

![afiveth](/assets/img/180508/fiveth.PNG)
![asixth](/assets/img/180508/sixth.PNG)
![aseventh](/assets/img/180508/seventh.PNG)

Now, a project is imported. But attention is, the above is only the server is different, to do the corresponding modification, may also be different JRE and so on, the same need to repeat the above steps to make corresponding changes. Just skip over here.But, after the corresponding modification. There will be some special problems. For example, the files in project are not wrong, but there will be a small red fork or a red exclamation mark on the document. The following is the perfect solution for my meeting, which is recorded below for your reference.

*About red fork：*

When the eclipse is basically well configured.You need to check the settings folder in the project directory.

![aeighth](/assets/img/180508/eighth.png)
![aninth](/assets/img/180508/ninth.png)
![atenth](/assets/img/180508/tenth.png)

*About Red exclamation mark：*

Find the red sigh in front of the eclipse project, the red exclamation mark in front of the eclipse project, the red exclamation mark in front of the eclipse project, the red sigh in front of the eclipse project, the right mouse button, in the right button menu, in turn: Build Path config build path or Build Path configure .

![aA](/assets/img/180508/A.png)
![aB](/assets/img/180508/B.png)

After clicking on the configure build path of the eclipse project, in the pop-up window, find the Libraries tab, you can see that some jar packages are red cross numbers, the jar package is the jar package that can't find the corresponding file, the red sigh in front of the eclipse project, probably because of the project imported from the outside or because it is because Some of the files were deleted before the red exclamation. Find the jar package that is missing from these eclipse projects and delete it.

![aC](/assets/img/180508/C.png)

In the eclipse project, after deleting the extra jar package, or after all the jar packages are deleted, click the Add JARs function to find the jar package in the current project and import it into the eclipse project.

![aD](/assets/img/180508/D.png)
![aE](/assets/img/180508/E.png)

After importing the eclipse project, click the OK button, you can import the jar package into the eclipse project, and the phenomenon of red exclamation before the eclipse project disappeared.

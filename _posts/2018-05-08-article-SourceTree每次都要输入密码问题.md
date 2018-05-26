---
layout: post
title: SourceTree保存密码--解决每次pull、push都要输入两次密码的问题
key: 20180510
tags: Git SourceTree
---

# SourceTree保存密码--解决每次pull、push都要输入两次密码的问题

1、SourceTree每次Pull和Push时都要输入密码，确实很不方便：

2、提供一个简单的解决方法，即在远程仓库的url中显示输入username和password，每次就不用再重复输入，当然也有一定的安全隐患，可根据实际情况决定是否采用。

1）选中菜单：Repository（仓库）-- Repository settings(仓库设置) --Remotes--选中url--Edit；

2）比如URL为：http://xxxxx/xxxx.git  修改为：http://username:password@xxxxx/xxxx.git  （即新增username:password@）

username和password分别为你登录的用户名和密码，之后就不用每次都输入密码了。


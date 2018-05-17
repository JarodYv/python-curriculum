---
title: 加密信息 — 教学笔记
language: zh-CN
embeds: "*.png"
...

# 简介

在这个项目中，孩子们将学习如何开发一个加密程序，可以跟朋友发送和接收加密信息。这个项目还将介绍字符串迭代。

# 在线资源

__本项目使用Python 3。__ 我们建议使用 [trinket](https://trinket.io/) 在线编写Python代码。这个项目包含如下Trinket:

+ [新建 (空白) Python Trinket -- jumpto.cc/python-new](http://jumpto.cc/python-new)

下面的trinket包含完整的工程:

+ [‘加密信息’ 完整版 -- trinket.io/python/402256078c](https://trinket.io/python/402256078c)

+ [‘友谊计算器’ 完整版 -- trinket.io/python/2e852cd687](https://trinket.io/python/2e852cd687)

# 离线资源

如果你愿意，本项目可以 [离线完成](https://www.codeclubprojects.org/en-GB/resources/python-working-offline/) 你可以点击本项目的'Project Materials'链接访问项目资源。这个链接有一个 'Project Resources' 部分，里面包含孩子们完成该项目所需的离线资源。请确保每个孩子都能获取了这些资源。这部分包含如下文件：

+ messages-finished/messages.py
+ messages-finished/friends.py

(上述所有资源都可以以zip压缩包的形式下载。)

# 学习目标

+ 迭代 (循环) 字符串变量;
+ `find()` 方法;
+ 取模(`%`)运算符.

# 挑战

+ 凯撒加密 - 手动加密解密一个字母或单词;
+ 可变密钥 - 允许用户自己输入密钥;
+ 加密解密信息 - 加密解密完整信息;
+ 友谊计算器 - 应用文本迭代来解决新的问题。

# 常见问题

+ 当用 `find()` 搜索或 `if char in alphabet:` 时，注意搜索是大小写敏感的。 可以用下面代码:

	```python
	message = input("Please enter a message to encrypt: ").lower()
	```

	在搜索前将输入变成小写。
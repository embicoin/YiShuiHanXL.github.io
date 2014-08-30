---
layout: post
title: bash笔记 
description: 记录关于bash的使用经验
category: opinion 
---

##1. RM 
###用rm批量删除文件时，排除某个文件
比如，删除当前目录下的所有.c文件，只保存filename.c：

    rm *[!filename].c


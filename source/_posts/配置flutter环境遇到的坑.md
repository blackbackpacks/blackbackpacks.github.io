---
title: 配置flutter环境遇到的坑
tags:
  - Git
  - flutter
originContent: ''
categories:
  - Git
  - Windows
toc: false
date: 2019-02-03 13:48:08
---

### 由于使用*flutter doctor*命令控制台显示“where不是有效的命令，无法找到git”,但是git命令可以用，其他的flutter环境变量也没有问题，经过一番搜索原来是系统环境变量path没有加*C:\windows\system32*
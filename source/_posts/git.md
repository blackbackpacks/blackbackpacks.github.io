---
title: git常用命令
date: 2018-09-21 17:22:10
tags: Git
categories: Git
---

![Alt text](/images/git.png)

图片取自 [阮一峰的网络日志](http://www.ruanyifeng.com/blog/2015/12/git-cheat-sheet.html)

* Workspace：工作区
* Index/Stage：暂存区
* Repostory： 仓库区（或本地仓库）
* Remote：远程仓库

<!--more-->
## 查看git当前配置

git配置在 __.git__ 文件夹config文件,默认隐藏文件夹，

``` bash
git config -l
#设置提交代码用户信息
git config [-global] user.name "name"
git config [-global] user.email "email address"
```

## git init

在当前目录新建git 仓库（repository）会生成 **.git** 文件夹

``` bash
git init
```

## git clone 命令

将远程源码下载/复制到本地当前目录

``` bash
 git clone [url]
```

## git pull 命令

更新当前文件夹源码

``` bash
git pull
```

## git commit 命令

提交暂存区到仓库区

``` bash
git commit -m [message]
```
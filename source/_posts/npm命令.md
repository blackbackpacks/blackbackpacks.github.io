---
title: npm命令本地安装和全局安装
date: 2018-11-21 15:36:19
tags: 
- npm
- node
- javascript
catgoties:
- javascript
---

**npm install** 四种命令模式的区别

<!-- more -->

| 名称                      | 描述                                                                                                     | 简写        |
| ------------------------- | -------------------------------------------------------------------------------------------------------- | ----------- |
| npm install **            | 安装 ** 模块，但不记录在package.json 里                                                                  | npm i **    |
| npm install --save **     | 安装 ** 模块并记录在package.json里，字段对应dependency,是产品环境必须以来的模块                          | npm i -s ** |
| npm install --save-dev ** | 安装 ** 模块 并记录在package.json里，字段对应 dev-dependency，是开发环境依赖的模块，测试类或者打包工具等 | npm i -D ** |
| npm install -global **    | 全局安装 ** 模块，但是不记录在package.json里，如果模块package.json 里有bin 配置，会自动链接，作为cli命令 | npm i -g ** |

> 参考 [如何正确的学习Node.js](https://i5ting.github.io/How-to-learn-node-correctly/#1090203)
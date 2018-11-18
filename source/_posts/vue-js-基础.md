---
title: vue.js 基础
date: 2018-11-06 15:03:49
tags: vue
categories:
- 前端
- vue
---
# vue 基础学习

## v-bind缩写

``` html
<!-- 完整语法 -->
<a v-bind:href="url">...</a>

<!-- 缩写 -->
<a :href="url"></a>
```

## v-on 缩写

``` html
<!-- 完整语法 -->
<input v-on:click="show">

<!-- 缩写 -->
<input @click="show">
```
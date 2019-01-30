---
title: 多个inline-block 元素baseline对齐解决办法
tags:
  - css
originContent: |-
  # 使用vertical-align

  垂直对其样式**vertical-align**负责行内元素垂直方向排列情况，不可继承它的默认值为*baseline*。

  ```css
  .inline-block{
  vertical-align:bottom;
  }
  ```
  推荐使用**vertical-align**:*bottom*，修改对其方式为非*baseline*。
categories:
  - 前端
toc: false
date: 2019-01-30 16:43:55
---

# 使用vertical-align

垂直对其样式**vertical-align**负责行内元素垂直方向排列情况，不可继承它的默认值为*baseline*。

```css
.inline-block{
vertical-align:bottom;
}
```
推荐使用**vertical-align**:*bottom*，修改对其方式为非*baseline*。
> 参考[RD1016: 各浏览器对常用行内替换元素的  'baseline' 位置理解不同](http://w3help.org/zh-cn/causes/RD1016)
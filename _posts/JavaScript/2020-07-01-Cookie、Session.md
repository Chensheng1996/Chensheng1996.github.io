---
layout: post
title: JavaScript---Cookie、Session
date: 2019-07-01
tags: JavaScript
---

## 什么时Cookie？
Cookie是存储在访问者计算机中的变量。每一台计算机通过浏览器请求某个页面时，就会发送这个Cookie。可以使用JavaScript来创建和获取Cookie的值。

## Cookie的兼容性

## Cookie的缺点

## 使用Cookie时的注意事项

## 如何删除一个Cookie？
为了删除Cookie，要修改expires，代码如下。
``` js
document.cookie = 'user=jack;expires=' + new Date();
```

## Cookie和Session的区别
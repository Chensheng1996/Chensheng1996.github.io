---
layout: post
title: JavaScript---Cookie、Session、LocalStorage、SessionStorage
date: 2019-07-01
tags: Web前端
---

## 什么时Cookie？
Cookie是存储在访问者计算机中的变量。每一台计算机通过浏览器请求某个页面时，就会发送这个Cookie。可以使用JavaScript来创建和获取Cookie的值。

## Cookie的兼容性
Cookie虽然为持久保存客户端数据提供了方便，分担了服务器存储的负担，但有很多局限性。
第一，每个特定的域名下，Cookie字段个数是有限的
1. IE6或更低版本中最多有20个Cookie。
2. IE7和之后的版本中最多可以有50个Cookie。
3. Firefox中最多有50个Cookie。

## Cookie的缺点

## 使用Cookie时的注意事项

## 如何删除一个Cookie？
为了删除Cookie，要修改expires，代码如下。
``` js
document.cookie = 'user=jack;expires=' + new Date();
```

## Cookie和Session的区别
``` js

``` 
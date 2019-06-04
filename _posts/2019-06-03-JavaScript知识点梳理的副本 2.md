---
layout: post
title: JavaScript知识点梳理
date: 2019-06-03 
tags: 博客   
---

　　经过各种找资料，踩过各种坑，终于使用 hexo 搭建个人博客初步完成了，域名目前用得时 github 的，我的 hexo 是 3.1.1 版本，hexo 不同的版本，很多配置都不一样。好吧，废话不多说了，开始吧。     

　　本篇文章累计了大量评论，和我的一些解答，读者有什么问题可以先看看评论，或者搜下关键字，如果还是有问题可以给我在评论里给我留言，问题很着急的可以加我 ＱＱ：1499065178　，或者给我发邮件：[leopardpan@icloud.com](mailto:leopardpan@icloud.com)  ，都可以，如果你已经搭建完成了，可以看看我的另一篇博客[HEXO进阶](http://baixin.io/2016/06/HEXO_Advanced/)，有讲如何能百度搜索你的博客、多台电脑使用HEXO发布博客等。我现在的博客是使用 Jekyll 搭建的，如果你想使用我现在的模板请看[Jekyll搭建个人博客](http://baixin.io/2016/10/jekyll_tutorials1/) 


### 构建Node工程
#### 1.安装Express框架
```node
npm install express -g  
npm install express-generator -g
```
#### 2.新建一个项目
```node
express -t ejs ProjectName // 使用ejs模板
```
#### 3.安装项目并启动
```node
npm install // 安装，生成node_modules
npm start // 端口号默认3000
```
<!-- <hr style="height:1px;"> -->
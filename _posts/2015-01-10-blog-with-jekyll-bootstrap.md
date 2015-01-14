---
layout: post
title: "Blog with Jekyll Bootstrap"
description: ""
category: 
tags: []
---
{% include JB/setup %}
##Jekyll-Bootstrap
Jekyll-Bootstrap 是一个完整的博客框架,基于它你可一快速的建立你自己的博客,相比自己徒手从jekyll入手建立方便了不少,它已经有很多地方配置好了,比如添加评论系统,较为方便的主题管理等等.
具体介绍可以看 [Jekyll Bootstrap](http://jekyllbootstrap.com/).

##如何使用
[官网文档](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)有详细介绍.这里简单记录一下:
jekyll serve(再博客目录下运行,可已实时本地调试.)[ads](http://localhost:4000/)
多说

多说是什么？

多说是追求最佳用户体验的社会化评论框，为中小网站提供新浪微博、QQ（QQ空间和腾讯微博）、人人、开心网、豆瓣、网易微博、搜狐微博、百度、淘宝、Google等多帐号登录并评论功能。它帮你搭建更活跃，互动性更强的评论平台。具有众多实用特性，功能强大且永久免费。

 
rake post title="Hello World"
rake page name="about.md"
rake page name="pages/about.md"
$ rake page name="pages/about"
# this will create the file: ./pages/about/index.html 
$ git add .
$ git commit -m "Add new content"
$ git push origin master



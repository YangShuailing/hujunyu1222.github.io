---
layout: post
title: "搭建个人独立博客"
date:   2016-04-11 21:57:00 +0800
categories: [git-pages, jekyll, markdown]
---

### 1.前言

我早就想搭建一个自己的博客了，由于拖延症晚期，所以一直到现在我才准备真正动手。_(:зゝ∠)_ 不多说，进入正题。
我主要采用的是`github-pages` + `jekyll` + `markdown` 这一套架构。主要分工如下：

- github-pages用于显示博客的主页，相当于把自己的博客挂在github上
- jekyll用于将用markdown写的博客转换为静态的html页面
- markdown用于编写博客，十分方便。


### 2.具体搭建过程

## 2.1 Github-pages

想要github-pages，首先你要拥有一个[Github](https://github.com/)账号。
完成注册后，新建一个**repository**,命名为`你的用户名.github.io`或者`你的用户名.github.com` ，这个命名规则必须的，这个repository就是你账号的github-pages，**每个账号只有一个！**，而对于其他的项目，每个项目可以有多个git-pages。
现在是个空的repository，我们暂时不管它。

## 2.2 Jekyll安装
Jekyll是默认支持markdown语法的，[markdown语法](http://daringfireball.net/projects/markdown/)简单易学，而且高效，无论是做笔记还是写心得都十分适合作为程序员的我们。

本地文件操作简单，不需要管理数据库。新建了一个文件，刷新一下，页面上就有了发布的文件。

+ Jekyll是基于**Ruby**环境的，如果你是使用MAC的用户，那你的电脑里应该默认安装了Ruby环境，而像我这样的windows8用户，就需要先[下载Ruby](http://rubyinstaller.org/downloads/)环境安装以及对应的**development kit**。安装完后下图：
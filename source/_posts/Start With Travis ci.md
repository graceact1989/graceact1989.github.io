---
title: Start With Travis ci
date: 2017-07-07
tags: travis-ci
categories: Coding
---

### Just Test Auto Push Blog Files. ###

在使用travis-ci进行blog自动发版时，遇到的困难有两个：

- 未明白${GH_TOKEN}参数的意义

		此参数为github上设置Personal access tokens

- 未明白.travis.yml文件中 branch only blog-source的含义

		这个设置为blog发布的静态页，所用的源码分支名字，blog-source为源码分支名字
		至今未明白，如何对blog源码在另外一个仓库的发布方式
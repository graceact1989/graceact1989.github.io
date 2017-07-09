---
title: Start With Git
date: 2017-07-09 22:50:06
tags: git
categories: Coding
---

### 总结个人使用Git过程中踩过的坑 ###

- 如何使用获取分支代码
		
		git clone XXX.git #获取master代码
		git branch -a #查看所有分支
		git checkout XXX #检出所需要的分支代码

- 对于在本地的git仓库如何上传到服务器

		1. 首先在服务器上创建一个空的仓库
		2. git remote add origin "创建好的服务器仓库"
		3. git push -u origin --all
		4. git push -u origin --tags



7/9/2017 11:10:13 PM 

----------

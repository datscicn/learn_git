---
title: GIT|GIT教程~3.GIT远程操作
date: 2019-01-01 00:00:03
tags: code
categories: GIT
---
<p align="center"><font face="微软雅黑" color=DarkGoldenRod size="8">GIT教程~3.GIT远程操作</font>

> 一、流程概览
1. 查看已有远程仓库
git remote -v
2. 远程仓库建立
3. 连接至多个远程仓库
```
git remote add origin git@github.com:datscicn/learn_git.git
git remote add origin_gitee git@gitee.com:datscicn/learn_git.git
git remote add origin_wacai git@git.caimi-inc.com:longding/learn_git.git
```
4. 远程
```
git push -u origin master
git push -u origin_gitee master
git push -u origin_wacai master
```

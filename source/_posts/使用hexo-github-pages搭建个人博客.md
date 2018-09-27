---
title: 如何使用hexo + GitHub Pages搭建个人博客
date: 2018-09-26 10:36:22
tags: 
- Hexo
- GitHub
- NexT
categories:
- 教程
---

本教程介绍如何在Windows使用[Hexo](https://hexo.io/zh-cn/ "Hexo")搭建一个个人博客，并部署到GitHub的[GitHub Pages](https://pages.github.com/ "GitHub Pages")服务中。
<!-- more -->
1. 准备工作 
    * 申请一个GitHub账号
    * 安装node和npm
2. 发布新文章
    在博客目录 source\_posts 创建名为xxx的新文章
    ```
        hexo n "xxx" 
    ```
    打开位于博客目录 source\_posts 的xxx.md文件，使用[markdown语法](https://github.com/younghz/Markdown "markdown语法介绍")进行编辑
    ```
        ---
        title: xxx
        date: 2018-09-27 14:37:26
        tags:
        ---
        //在此处开始编辑
    ```
    编辑完毕之后，执行Hexo命令
    ```
        //清空资源文件，可选操作
        hexo clean 

        //重新生成资源文件
        hexo generate (或 hexo g)

        //本地发布文章
        hexo server (或 hexo s)

        //发布文章到主分支
        hexo deploy (或 hexo d)
    ```
    
    

---
layout: page
title:  "9.9学习总结"
subtitle: "搭建个人技术博客"
date:   2020-09-09 20:04 
categories: GIT
---

# 搭建个人技术博客
 使用GitHub pages +jekyll 快速部署博客
 - GitHub pages:
      - 定义:给所有用户提供一个个人主页
      - 如何访问：用户名.github.io
      - 如何编写一个主页:建立一个用个人域名为项目名的远程管理仓库，只需要向该远程版本仓库中的master分支提交代码即可(该代码中必须有一个为index.html文件)
 -  jekyll
  - 定义:可以将markdow语法启动编译成 html语法的一个工具  
  - 安装:在github网站上已预安装
  - 使用:当请求个人域名时github服务器会读取仓库(以个人域名命名的运程管理仓库)中的master分支中的代码，如该代码为markdow语法会自动调用jekyll将其编译为html并返回客户端
- 建立以个人域名为项目名的远程管理仓库
- 访问一个主题网址为: http://jekyllthemes.org/选择一主题，将其代码复制到master分支
- 以上两步可合二为一，在主题仓库点fork,点击setting设置仓库名即可
- 将远程版本库的代码克隆到本地
- 修改配置文件以及页面内容
- 书写博客
---  
   备注信息
> 一些备注信息使用引用符号

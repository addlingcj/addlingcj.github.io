---
layout: page
title:  "Linux.nginx"
subtitle: "nginx安装与使用"
date:   2020-09-27 19:35
categories: 系统
---

# 配置apt-get阿里云镜像源
- apt-get的工作原理（下载软件 工作分两部，搜索在本地）
- apt-get update  更新网站软件下载消息
- apt-get install 软件名 下载软件
- apt-get的配置文件（修改远程连接为阿里云的镜像）

# 安装nginx
- 安装 
	- 如何判断nginx安装成功
	- 启动 `service nginx start`
	- 停止 `service nginx stop`
	- 重启 `service nginx restart`
- 修改nginx配置文件
	- 主配置文件 nginx.conf
	- 辅助配置文件 ./etc/nginx/sites-enabled
		- sites-enabled里面的所有文件 
		- conf.d里面的所有conf文件
	- 将sites-enabled里面的default（nginx中默认的网站配置文件）更改其网站根目录
- 查看错误日志文件  cd /
                     /var/log/nginx

# linux系统
- 常见命令
	- cd 切换地址
	- ls 查看当前文件夹下文件
	- mkdir 创建文件夹 
	- touch 创建文件
	- pwd  查看当前所在位置
	- rm  命令用于删除一个文件或者目录
- 权限
	- chmod -R 777 目录路径（访问网站需要将网站根目录设置为777权限）
	- 读 写 执行分别被安排的数字为 1,2,4 

# VIM
- 命令行模式(esc/默认)
	- 底行命令 ：引导
	- 快捷键
		- yy 拷贝当前行
		- dd 清除字符
		- u  撤回
		- p  在当前光标后粘贴
- 编辑模式（aAiI）
       - a 转为编辑模式
	   - esc 退出编辑模式

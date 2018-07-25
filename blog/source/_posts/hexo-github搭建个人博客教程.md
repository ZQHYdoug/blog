---
title: hexo+github搭建个人博客教程
date: 2018-07-24 11:34:07
tags:
---
hexo+github搭建个人博客
# hexo
一.hexo安装前得准备node
###特点:快速.简介且高效的博客框架
###环境:基于node(v8.11.3)
1.环境检测 cmd -->node -v
2.安装node环境
   官网nodejs.org下载 傻瓜式安装
###二.安装git(版本控制器)
   直接百度官网下载
   SVN or 码云
   github程序员交流平台
###三.安装hexo
cmd命令:npm install 包名 -g1
npm install hexo-cli -g
npm:基于node的包管理器,类似于ios的 App store 
    通过npm可以下载安装需要的插件或者框架
install:安装.导入的意思
-g: 表示全局安装(在任何目录都可以使用)
cli:框架
###四.初始化一个博客项目
  1.hexo init blog(项目名)
  2.切换到项目目录
    cd 项目名
  3.安装项目依赖包
    npm install 
  4.启动 hexo
    hexo server
  5.在浏览器输入 localhost:4000
  6.新建文章
    hexo new "名字"
 7.设置标题属性
   在config.yml里面
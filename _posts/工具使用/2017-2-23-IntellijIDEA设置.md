---
layout: post
title:  IntelliJ IDEA上手设置
date:   2017-02-23 22:59:01 +0800
categories: 工具使用
tag: IntelliJ AndroidStudio
---

* content
{:toc}

## 前言
注：以下是基于以前的笔记，现在做的整理:)

>以前做Java开发相信大家都用过eclipse，这款IDE功能强大，而且集成插件Market，有极高的扩展性，但是相信大家也都对其不支持自动保存，缺少代码检查（最明显的就是工程一导入就一堆文件标红[抓狂~]），启动速度慢等缺点嗤之以鼻。
>随着生产力工具的不断发展，越来越多更加智能，更加快速的IDE被不断的开发出来，比如目前Java开发最火的IDE-[IntelliJ IDEA](http://www.jetbrains.com/idea/).
>上手IntelliJ IDEA 我习惯做一定的设置来提高我的生产效率。

### 1、禁止自动打开上次的工程
Appearance & behavior>System Settings> 右边的Reopen last project on startup
### 2、鼠标悬停显示文档，格式化&导包提示
Editor>General> 右边的Show quick doc on mouse move、Formatting.
### 3、显示行号，显示方法分隔线
Editor>General>Appearance> 右边的Show line numbers 和 Show method separators.
### 4、优化导包
Editor>General>Auto Import> 右边的  
	Optimize imports on the fly：优化导包，格式化代码时会删掉多余的导包。
	Add unambiguous imports on the fly：敲代码时，敲简单类名就帮你把包导了。
### 5、修改字体和大小
Editor>Colors & Fonts>Font> 右边的Show only monspaced fonts 把字体设为Consolas，大小16.
### 6、修改新建文件文件头（头注释）
Editor>File and Code Templates> 右边的File Header修改。
### 7、修改文件编码为UTF-8
Editor>File Encodings> 右边 改UTF-8。


# LessOrMore


致谢
====================================
+ 感谢[Less官网](http://lesscss.cn/)的样式，本Jekyll框架的样式都是基于Less官网的样式直接拷贝过来的。只是重构了JS，并且加入了Jekyll语法而已。
+ 感谢[Github](https://github.com/)提供的代码维护和发布平台
+ 感谢[Jekyll](https://jekyllrb.com/)团队做出如此优秀的产品


使用
====================================

配置
------------------------------------

`LessOrMore`项目需要配置的只有一个文件`_config.yml`，打开之后按照如下进行配置。

> 特别注意`baseurl`的配置。如果是`***.github.io`项目，不修改为空''的话，会导致JS,CSS等静态资源无法找到的错误

``` bash
name: 博客名称
email: 邮箱地址
author: 作者名
url: 个人网站
### baseurl修改为项目名，如果项目是'***.github.io'，则设置为空''
baseurl: "/LessOrMore"
resume_site: 个人简历网站
github: github地址
github_username: github用户名称
FB:
  comments :
    provider : xxxxxx
    duoshuo:
        short_name : xxxxxxx
    disqus :
        short_name : xxxxxxx
```

如何写文章
------------------------------------

在`LessOrMore/_posts`目录下新建一个文件，可以创建文件夹并在文件夹中添加文件，方便维护。在新建文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`的相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

``` bash
---
layout: post
#标题配置
title:  标题
#时间配置
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


我是正文。我是正文。我是正文。我是正文。我是正文。我是正文。
```

执行
------------------------------------

``` bash
jekyll server
```

效果
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。

关于作者
====================================

程序员，来自福建长汀。目前在珠海从事Java开发。这套开源框架基于Jekyll，我使用的是LessOrMore这个改装项目，当然的，加了自己的一些修改。有喜欢的用户可以clone下来。
酝酿博客已经很久了，在很多平台上也尝试过写一些博客，但是博主我实在太懒了，很难有动力去更新内容。所以才有了这个项目，希望能写出些有用的东西，同时欢迎访问我的gitHub主页https://github.com/seline100。

---
title: 轻松拥有自己的LemonBlog🍋！
author: monohue
layout: post
excerpt: 说真的，有手就行
---

# LemonBlog🍋
LemonBlog🍋可以让您自动生成一个轻量级的、基于Jekyll的静态网站。  
来康康[演示网站](http://lemonblog.magi.red)！  
LemonBlog🍋只需要您提供Markdown文档，之后所有事务都会由系统包办，包括目录，样式……  
文章基于LemonBlog🍋 v0.0.1 alpha

# 如何拥有自己的LemonBlog🍋
LemonBlog🍋的获取方式非常简单！
## 一！拥有Github账号
登陆[Github](https://github.com)，注册一个自己的账号。
## 二！获取LemonBlog🍋
[在Github上新建一个库（repository）](https://github.com/new)，点击导入库的链接。![导入库]({{ site.url }}/downloads/tutorial-import.png)  
在链接栏输入 https://github.com/MonoHue/LemonBlog ，再给你的库取一个好听的名字，最后点击**开始导入**。

## 三！运行你的网站
在库的最右，点击设定，然后拉到最下方，有一个Github Pages。  ![Github Pages]({{ site.url }}/downloads/tutorial-pages.png)
按照上图选择，你就拥有你的LemonBlog🍋了！通过显示的链接，你可以跳转到你专属的LemonBlog🍋！

## 四！给你的网站一个新名字
你需要在库内的代码里，找到很显眼的_config.yml，进去之后是这样的。![_config.yml]({{ site.url }}/downloads/tutorial-config.png)  
然后你需要修改_config.yml一些内容,你可以点击最右边"电脑，笔，垃圾桶"的笔来修改：
> BaseUrl: "LemonBlog.magi.red"  
> 把【三！运行你的网站】中生成的链接（要加http://)完整的放在引号内。  
> 如果有自己的域名并且愿意使用，把你域名写在双引号内，同时需要改一下DNS解析。   
> 
> WebName: "LemonBlog🍋"  
> 在引号内修改你的网站名。  
> 
> Slogan: "The Slogan of the Website"  
> 网站主页的标语。  
> 
> WebSuffix: " - LemonBlog"  
> 显示在tab内的内容，类似"百度 - 百度百科"。

然后点击最下方的提交就可以了。

# 一起开发LemonBlog🍋！
我们期待和您一起开发LemonBlog🍋！  
**[LemonBlog🍋的Github地址](https://github.com/MonoHue/LemonBlog)**

# 进阶：修改你的网站
可以参考以下链接对你的网页做出改进：
- [Primer CSS](https://primer.style)
- [Jekyll](https://jekyllrb.com)
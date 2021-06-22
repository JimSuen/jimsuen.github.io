# 介绍

[Jim Suen's Blog](https://jimsuen.github.io/)

一款 jekyll 主题，简洁纯净(主题资源请求<20KB)，未引入任何框架，秒开页面，支持自适应，支持全文检索，支持夜间模式

## 感谢

感谢主题作者 TMaize（[GitHub 地址](https://github.com/TMaize/tmaize-blog)）

[夜间模式代码高亮配色](https://github.com/mgyongyosi/OneDarkJekyll)

## 使用

文章放在`_posts `目录下，命名为 `yyyy-MM-dd-xxxx-xxxx.md`，内容格式如下

```
---
layout: mypost
title: 标题
categories: [分类1, 分类2]
---
文章内容，Markdown格式
```

文章资源放在 `posts` 目录，如文章文件名是 2019-05-01-theme-usage.md，则该篇文章的资源需要放在 posts/2019/05/01 下,在文章使用时直接引用即可。当然了，写作的时候会提示资源不存在忽略即可

```
![这是图片](xxx.png)

[xxx.zip 下载](xxx.zip)
```

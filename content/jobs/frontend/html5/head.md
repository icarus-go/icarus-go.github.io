---
title: "Head"
date: 2023-03-14T00:07:23+08:00
draft: false
tags:
  - frontend
categories:
  - Work
series:
  - 前端技术
---

- <head> 元素包含了所有的头部标签元素。
- 在 ` <head>` 元素中你可以插入脚本（scripts）, 样式文件（CSS），及各种meta信息。
- 可以添加在头部区域的元素标签为: <title>, <style>, <meta>, <link>, <script>, <noscript> 和 <base>。

| element name | desc |  remark | required |
| ---- | ---- | ---- | ---- |
| title | 不同文档的标题 | 收藏夹的标题 | true | 
| base | 基本链接地址，或者目标的前缀 | - |  false | 
| link | 定义了与外部资源的关系  | - | false | 
| style | 定义了 HTML 文档样式文件引用地址 | - | false | 
| meta | 元数据不显示在页面上，但是会被浏览器解析 | - | false |
| script | 定义了客户端的脚本文件 | - | false | 


## Link

```html
<head> 
	<link rel="stylesheet" type="text/css" href="theme.css" /> 
</head>
```

## meta

- 设置编码格式
```html
<head>
	<meta charset="utf-8" />
	<title> .... </title>
</head>
```



---
title: "HTML"
date: 2023-03-14T00:07:23+08:00
draft: false
tags:
  - frontend
categories:
  - Work
series:
  - 前端技术
---
# 正文
- HTML5
```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="utf-8" />
		<title> Document </title>
	</head>
	<body>
		....
	</body>
</html>
```
- 最新版
- 比较松散 
- 变化
	- 增加了很多语义化的标签
		- header 头部内容
		- nav 导航
		- footer 底部
		- article 文章区域
		- section 某个区域
		- aside 侧边 

## List 属性

```html
<body>
	<input type="text" list="stars" value="input your idor"/>
	<datalist id="stars">
		<option>蔡徐坤</option>
		<option>胡歌</option>
		<option>other</option>
</body>
```
##  input email 属性

```html
<input type="email" /> 
```
## input tel 属性
```html
<input type="tel" />
```

## input number 属性
```html
<input type="number" />
```

## input url 属性
```html
<input type="url" />
```
## input search 属性
```html
<input type="search" />
```

## input range 属性区域
```html
<input type="range" />
```

## input date 日期属性
```html
年月日 <input type="date" />
月份 <input type="month" />
星期几 <input type="week" />
```
## input color 颜色
```html
<input type="color" /> 
```
## input placeholder 属性
```html
<input type="text" placeholder="请输入用户名称"/>
```
## input autofocus 自动获得焦点属性
```html
<input type="text" autofocus /> 
```
## input file 属性 and multiply
```html
<input type="file" multiply />
```
## input autocomplete 自动完成属性
```html
<form action="" >
	<input type="text" autocomplete="on" name="userName" />
	<input type="submit" />
</form>
```
## input reuqired 属性
```html
<input type="text" reqiured />
```

## input accessKey 属性 
- 代表获得焦点时使用的键
- [accesskey - HTML（超文本标记语言） | MDN (mozilla.org)](https://developer.mozilla.org/zh-CN/docs/Web/HTML/Global_attributes/accesskey)
```html
<input type="text" accesskey="c" />
```
##  XHTML， HTML4
- XHTML
	- 严格的HTML
	- 有 3 个版本，现在用的比较少了
- HTML4
	- .. 


# Reference
- [MDN Web Docs (mozilla.org)](https://developer.mozilla.org/zh-CN/)
- [HTML（超文本标记语言） | MDN (mozilla.org)](https://developer.mozilla.org/zh-CN/docs/Web/HTML)
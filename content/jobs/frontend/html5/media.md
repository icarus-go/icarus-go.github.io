---
title: "Media"
date: 2023-03-20T02:14:13+08:00
draft: false
tags:
  - frontend
categories:
  - Work
series:
  - 前端技术
---

# 正文
## embed 
- Embed标签是HTML中的一种插入外部内容的标记。通常用于在网页中嵌入视频、音频、Flash等多媒体文件，以及其他类型的可嵌入的媒体。
```html
<embed src="url" type="mime_type" width="pixels" height="pixels"> </embed> 
```
- src 指定的地址
- type 是mime类型
	- MIME（Multipurpose Internet Mail Extensions）类型是一种用于指定Web浏览器和其他Internet应用程序中的内容类型的标准标识符。以下是常见的MIME类型：
	- text/plain：纯文本文件
	- text/html：HTML文件
	- application/json：JSON文件
	- image/jpeg：JPEG图片
	- image/png：PNG图片
	- image/gif：GIF图片
	- audio/mpeg：MP3音频文件
	- video/mp4：MP4视频文件
	- application/pdf：PDF文件
	 - application/msword：Microsoft Word文件
	- application/[vnd.ms](http://vnd.ms)
	- excel：Microsoft Excel文件 - application/[vnd.ms](http://vnd.ms)
	- powerpoint：Microsoft PowerPoint文件
	- application/zip：ZIP压缩文件

- width 宽
- height 高

## audio 音频类 
- audio 标签是 HTML5 新增的标签，用于在 web 页面中嵌入音频文件。通过设置 src 属性，将音频文件的链接地址指定给 audio 标签，控制台就可以播放音频文件了。
- attribute
	- src
	- controls 显示播放器控件，播放暂停音量等
	- autoplay 是否自动播放
	- loop 循环播放
		- 循环播放次数
		- -1 无限 播放
	- preload 预加载音频 
	- muted 静音播放
	- volume 音量大小，值为 0.0 ~ 1.0
## video 视频
- video标签是HTML5新增的标签之一，用于在网页中嵌入视频。
- 使用video标签可以为用户提供一个内置的媒体播放器，使得视频的播放更加方便和自然。video标签的基本结构如下
```html 
<video src="video.mp4" controls>  Your browser does not support the video tag.</video>
```
- 其中
	- `src`属性指定视频文件的URL
	- `controls`属性可以在视频上方添加一个默认的控制条，用户可以通过控制条来控制视频的播放、暂停、音量等。如果浏览器不支持video标签，则会显示`Your browser does not support the video tag.`的提示信息。
	- 除了`src`和`controls`属性，video标签还支持很多其他的属性和事件
	- `autoplay`自动播放
	- `loop` 循环播放
	- `poster` 预览图
	- `preload` 预加载
	- 可以根据需要来使用。
	- 总的来说，video标签是一个非常方便的工具，可以让开发者在网页中嵌入视频，并为用户提供一个默认的媒体播放器。

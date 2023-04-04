---
title: "Css"
date: 2023-04-04T14:29:32+08:00
draft: true
---

# What's CSS3

- CSS是层叠样式表（Cascading Style Sheets）的缩写，是一种用来描述HTML或XML等文档的表现层的语言。
- 它主要用于控制网页的布局、字体、颜色、背景、边框、动画效果等方面的样式。

## css语法结构和基本规则
```css
/* 选择器 */ 
selector {
	attribute name : attribute value;
	... 
}

/* 若有多个*/
selectN {
	attriubte name : aittrubte value;

}
```

## 如何使用?
- 样式表可以放在 HTML 稳当当额 head 部分，也可以单独存储，样式表可以通过 `link` 元素或 `@import` 来引入到 HTML 文档中。
```html
<link rel="stylesheet" type="text/css" href="style.css" />
```
### 优先级是什么？
- `!important` > `inline style` > `id selector` > `Class selector/attribute selector/pseudo-class selector ` > `* selector`
- 当优先级相等时
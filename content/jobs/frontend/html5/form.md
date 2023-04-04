---
title: "Form"
date: 2023-03-15T00:50:02+08:00
draft: true
tags:
  - frontend
categories:
  - Work
series:
  - 前端技术
---

- `<form>`
	- attribute
		- action 提交目标 URL
		- method 提交的 http Method
		- name 区分表单
	- child element
		- `<label>` 
			- attribute
				- for
					- 指定控件的 id
		  - `<select>` 下拉框
		- `<option>` 下拉选项
			- attribute
				- selected="selected" 选中效果
		- `<textarea>` 文本域
		-  `<input>` 
			- type
				- text 文本框
				- password 密码框
				- radio 单选
					- 使用 `name` 来对该组单选进行关联
				- checkbox
					- 复选框
				- button
					- 按钮
				- submit
					- 提交按钮
				- reset
					- 重置表单的内容
				- image 图片
			- required
				- 是否必填
			- autofocus
				- 用于指定表单中的某个输入控件是否自动获取焦点。
			- placeholder
				- 用于设置输入控件的占位符文本
			- autocomplete
				- 用于控制浏览器是否自动填充表单中的输入控件
		- `<button>` 按钮
		- `<fieldset>`用于将表单中的多个输入控件分组
		- `<legend>` 用于定义fieldset元素的标题。
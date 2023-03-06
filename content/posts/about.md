+++
title = "About Me"
description = "Hugo, the world's fastest framework for building websites"
date = "2023-03-06T22:24:35+08:00"
timezone = "UTC+8"
tags = ["基础信息"]
categories = ["基础信息"]
author = "Quinson"
weight = 999
+++

```go
package main

import "fmt"

func main() {
	var skill = []string{
		"Go",
		"Java",
		"Docker",
		"Postgres",
		"MySQL",
		"Redis",
		"Kafka",
		"RabbitMQ",
		"Linux",
		"Git",
	}

	fmt.Println("Name 蔡昆森")
	fmt.Println("Birthday 1996/06/19")
	fmt.Println("Gender Man")
	fmt.Println("Email kevinicarus@163.com")
	fmt.Println("From China GuangDong ShanTou")
	fmt.Printf("Skill %v\n", skill)

	fmt.Sprintf("Want %v", []string{"网站构建", "微服务", "AI", "大数据", "区块链"})
}

```
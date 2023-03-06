---
title: "Homebrew下载过慢解决方案"
date: 2023-03-06T22:24:35+08:00
timezone: UTC+8
description: "初始化Mac OS X"
tags: ["MacOS"]
categories: ["PC"]
series: ["Homebrew"]
---
## Switch home brew git repo

### 切到 homebrew 目录
```bash
cd "$(brew --repo)"
```

- 如果你需要查看当前目录下,已经使用了哪些源,可以使用, 初始化状态下是 `github`
```bash
git remote -v 
```

### 删除源
```bash
git remote rm origin 
```

### 添加阿里源
```bash
git remote add origin https://mirrors.aliyun.com/homebrew/brew.git
```

### 切换阿里源
```bash
git remote set-url origin https://mirrors.aliyun.com/homebrew/brew.git
```

## 切换到 homebrew core 目录
```bash
cd "$(brew --repo)/Library/Taps/homebrew/homebrew-core"
```

### 删除源
```bash
git remote rm origin
```

### 更新源
```bash
# 添加源
git remote add origin https://mirrors.aliyun.com/homebrew/homebrew-core.git

# 切换成阿里源：
git remote set-url origin https://mirrors.aliyun.com/homebrew/homebrew-core.git
```

## homebrew-bottles (主要负责 cask, 即 GUI )
```bash
cd "$(brew --repo)"/Library/Taps/homebrew/homebrew-cask
```

### 删除源
```bash
git remote rm origin
```

### 更新源

- 阿里云没有提供 cask 源, 下列提供可替换的源

> Homebrew 官方源（https://github.com/Homebrew/homebrew-cask）
> 
> Fallback 官方源（https://github.com/Homebrew/homebrew-cask-versions）
> 
> 中科大源（https://mirrors.ustc.edu.cn/homebrew-cask/）
> 
> 清华大学源（https://mirrors.tuna.tsinghua.edu.cn/homebrew-cask/）
> 
> 华中科技大学源（https://mirrors.hust.edu.cn/homebrew-cask/）
> 
> 中国科学技术大学源（https://mirrors.ustc.edu.cn/homebrew-cask/）
> 
> 上海交通大学源（https://mirrors.sjtug.sjtu.edu.cn/homebrew-cask/）
> 


- 我们选中其中一个进行替换, 以中科大源为例
```bash
git remite add origin https://mirrors.ustc.edu.cn/homebrew-cask.git
git remote set-url origin https://mirrors.ustc.edu.cn/homebrew-cask.git 
```
---
title: "Mac mini 2018 装显卡坞的折腾之旅"
date: 2023-03-07T00:22:52+08:00
draft: false
tags: ["MacOS"]
categories: ["PC"]
series: ["硬件"]
---

# 起因

- 玩 android 模拟器有点卡
- 用网页云游戏玩的也卡
- 打开自家开发的 CRM 前端页面也卡

进而怒从胆边生，决定购置一款显卡，但是我是 Mac mini, 只能选择外接显卡的方式了。

- 凭借 CS （叉腰）专业，决定先买一款显卡坞，刚好了解到 B 站有 Up 主自制了一款显卡坞，所以决定入手一试。

# 经过

## 选显卡坞

- 市面上有很多款显卡坞，有的支持 1660X 以上的，也有的不支持的。
- 我大概扫了一眼，觉得稍微好看一点（装逼）的都要 2k 左右，实在不符合我的人设（贫穷），所以我看到 `逍遥君` 自制的 这款显卡坞，我才觉得是那么亲切（便宜），性能还挺高，损耗也比较少（我没实测，我不在乎损耗，大概上感觉不会比贵东西差多少），按照 `逍遥君`的说法是，比一般的显卡坞更强。
- 毫无疑问，就它了。


testing ....
sdsdasds


## 选显卡

- 结论
> 我买了 RX 580 2048 SP
> 
> 发现有问题
> 
> 补了 2304 SP

- 选对了显卡可以免驱，免折腾，免第三方驱动。
- 选错显卡毁一生~
- 强调注意 RX 580 的 流处理器问题（仅支持满血版 即 2304 SP），闲鱼大概 260 左右，非满血版 200 左右。
- RX 580 默认都是矿卡 （其他请参考更多）

### 雷雳 3 一体式 eGPU 产品
-  Blackmagic eGPU 和 Blackmagic eGPU Pro
-  Sonnet Radeon RX 570 eGFX Breakaway Puck
-  Sonnet Radeon RX 560 eGFX Breakaway Puck
- [博主自选] ***Gigabyte RX 580 Gaming Box*** 

### AMD 系列
- Radeon RX 6800、 6800XT、6900XT
	- 推荐用于上述图形卡的雷雳 3 扩展配件：
	-   Sonnet eGFX Breakaway Box 650W[4](https://support.apple.com/zh-cn/HT208544?caller=baiduansbx&cid=baiduansbx10#footnotes)
	-   Razer Core X[4](https://support.apple.com/zh-cn/HT208544?caller=baiduansbx&cid=baiduansbx10#footnotes)
- AMD Radeon RX 6600 XT
- MacOS Monterey 12.1 或者以上
	- 推荐使用的图形卡包括 Sapphire Nitro Radeon RX 6600 XT
	- 推荐用于以下图形卡的雷雳 3 扩展配件：
		-   Sonnet eGFX Breakaway Box 550W[4](https://support.apple.com/zh-cn/HT208544?caller=baiduansbx&cid=baiduansbx10#footnotes)
		-   Razer Core X
- 便宜但默认矿卡系列， 
	- AMD Radeon RX 470、RX 480、RX 570、RX 580 和 Radeon Pro WX 7100
	- 这些图形卡基于 AMD Polaris 架构。
	- 推荐的图形卡包括 Sapphire Pulse 系列和 AMD WX 系列。
	- 支持但是注意 RX 580
	- 有流处理器之分，2304 SP & 2048 SP.
	- 据说 Mac mini 2018 是不支持 2048 SP（别问我为什么知道 T_T ）
- 还有更多，请查看连接 [苹果官方原文 Mac mini 2018（或 inter CPU 支持的显卡）](https://www.baidu.com/link?url=_e4-oJOVI7w_H0bedLVXjhT0uFbVv1snlowyqfmAQoyAPX2-2xm3pCOj2lDKSQxGKPM11NicqrE3xVWJKe7UXCbGhLI1ZJuQRKZpJIIc0ua-c-L5u01sbtqmOVGoyf9z&wd=&eqid=bcda126b00048fa70000000264094b16)

##  怎么装

- 怎么装显卡坞其实`逍遥君`给出了一个具体的视频，但是我觉得不够具体，这就是我为什么想写这篇文章的主要原因！

# 结果

- 待完结结果图（其实是好评图）

## 引用

- [技术UP花费三个月，自制B站最快雷电显卡坞_哔哩哔哩_bilibili](技术UP花费三个月，自制B站最快雷电显卡坞_哔哩哔哩_bilibili)
- [逍遥君DIY的个人空间_哔哩哔哩_bilibili](https://space.bilibili.com/245020379?spm_id_from=333.337.search-card.all.click)
- [苹果官方原文 Mac mini 2018（或 inter CPU 支持的显卡）](https://www.baidu.com/link?url=_e4-oJOVI7w_H0bedLVXjhT0uFbVv1snlowyqfmAQoyAPX2-2xm3pCOj2lDKSQxGKPM11NicqrE3xVWJKe7UXCbGhLI1ZJuQRKZpJIIc0ua-c-L5u01sbtqmOVGoyf9z&wd=&eqid=bcda126b00048fa70000000264094b16)
- [装了显卡后如何 OS 上如何使用](https://support.apple.com/zh-cn/HT208544?caller=baiduansbx&cid=baiduansbx10#footnotes))
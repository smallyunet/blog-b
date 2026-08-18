---
title: Proof of AI Token 消耗量
date: 2026-08-18 15:47:36
tags:
- 代币
---

突发奇想，假如用 CodeX 里的 Token 消耗量用作某种挖矿的手段，怎么样？

<img src="1.png" width="100%">

目前的设计是：
1. 用户自己上报 Token 消耗量；不使用任何手段验证数据真实性
2. 用户上报的 Token 消耗量作为权重；同一个 epoch 汇总全部 miner 的消耗量作为比例
3. 每个 epoch 一天的时间；每个 epoch 释放 7200 代币；之后定时减半

形式上，miner 下载安装一个 Macos App，打开后会常住在 menu 区域，每天提交一次当天的 Token 消耗量（需要 Base 链上的 gas 费），根据概率获得代币：

<img src="2.png" width="40%">

GitHub 仓库地址：https://github.com/smallyunet/agentore

---

相关文章：
- 《[假如启动一个叫 Oiia Network 的以太坊 PoS 网络](https://b.smallyu.net/2025/01/28/%E5%81%87%E5%A6%82%E5%90%AF%E5%8A%A8%E4%B8%80%E4%B8%AA%E5%8F%AB-Oiia-Network-%E7%9A%84%E4%BB%A5%E5%A4%AA%E5%9D%8A-PoS-%E7%BD%91%E7%BB%9C/)》2025-01-28
- 《[BitDoge](https://b.smallyu.net/2026/01/20/BitDoge/)》2026-01-20




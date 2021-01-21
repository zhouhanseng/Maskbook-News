---
layout: post
lang: zh-Hans
template: Simplified Chinese
date: 2021-01-20
timezone: 8
type: ''
tags: []
en: []
ja: []
zh-Hant: []
title: 悬赏｜Mask Network 赏金计划全攻略
description: ''
location: 上海
image: ''

---
![]({{ site.baseurl_root }}/uploads/1-30.png)

Mask Network 是一款构建在现有社交网络平台之上的开源产品，并自正式运行以来一直坚持着技术开源的理念，我们希望能够借助社区以及开发者的力量来完善技术，丰富产品功能，为用户带来更好的使用体验。目前为止，Mask Network 已经在以太坊众筹平台 Gitcoin 上已经发布了共 10 个赏金计划，其中 2 个已完成。我们期待有越来越多优秀的开发者参与到 Mask Network 的建设中来，一同为所有的网络公民构建一个通往更加自由、开放的未来网络世界。

![]({{ site.baseurl_root }}/uploads/2-28.jpg)

以下是 Mask Network 正在进行的赏金计划，请点击相关链接查看赏金页面了解详情：

**1. 将 Solana 和 Serum 接入 Mask Network**

[https://github.com/DimensionDev/Maskbook/issues/1722](https://github.com/DimensionDev/Maskbook/issues/1722 "https://github.com/DimensionDev/Maskbook/issues/1722")

**时限：TBD**

**背景及介绍：**

Mask Network 最初被设计为一个与链无关的工具 ——— 不依赖于任何链，或者说支持所有链，并且一直围绕这一初衷不断发展。Mask Network 近期的重点是发展以太坊上的 DAPPs，但我们仍想整合更多的链和我们的小程序（plugin）上，为我们的用户提供更多的选择。因此，我们重新设计了 Mask Network 的内部钱包，将它拓展为一个多链钱包，当新的设计完成后，我们计划和以太坊以外的区块链开始新的整合。

**内容：**

**1. Solana 钱包**

Solana 是一个可拓展的、高性能的区块链项目。我们希望能整合他们的钱包创建、管理以及其他链上的相关操作。钱包整合可以被认为是这则悬赏的第二阶段任务，希望在我们正式公布我们的内部钱包标准后，能够开始这项整合工作。

**2. Serun UI 整合**

Serum 是一个链上去中心化交易所，支持订单簿交易以及合约交易。我们希望能够将该界面整合至 Mask Network 的行情交易插件中。用户在 Twitter 页面时，只要将鼠标悬停于任意 “$” 开头的通证符号时能够显示它的行情信息，并且会自动识别相关通证信息并链接至 Uniswap 交易对。整合 Serum 后，我们能够提供除 Uniswap 以外更多的交易选择，用户可以在不离开 Twitter 界面的情况下进行直接进行交易。Serum 是一个链上去中心化交易所，支持订单簿交易以及合约交易。我们希望能够将该界面整合至 Mask Network 的行情交易插件中。用户在 Twitter 页面时，只要将鼠标悬停于任意 “$” 开头的通证符号时能够显示它的行情信息，并且会自动识别相关通证信息并链接至 Uniswap 交易对。整合 Serum 后，我们能够提供除 Uniswap 以外更多的交易选择，用户可以在不离开 Twitter 界面的情况下进行直接进行交易。

**2. Sia Network 接入 Mask Network, 成为文件存储功能的另一服务提供商**

[https://github.com/DimensionDev/Maskbook/issues/2069](https://github.com/DimensionDev/Maskbook/issues/2069 "https://github.com/DimensionDev/Maskbook/issues/2069")

**平台：Gitcoin**

**经验要求：中级**

**类别：Mask 插件**

**时限：4 周**

**悬赏金额：1000 DAI**

**需求描述：**

目前，Mask Network 已经集成了 Arweave 作为去中心化文件存储与分享功能的技术提供方，通过 Arweave，用户能够上传任意类型的文件并将它附加到社交平台的帖子中。为了拓展这项功能，丰富用户的使用选择，我们希望能够集成更多技术提供方，如 Sia。你可能需要解决：创建帮助用户解决支付储存费用的微服务，具体可以参考我们之前和 Arweave 的合作相关。Sia 团队的官方引导会在此悬赏中直接列出。目前，Mask Network 已经集成了 Arweave 作为去中心化文件存储与分享功能的技术提供方，通过 Arweave，用户能够上传任意类型的文件并将它附加到社交平台的帖子中。为了拓展这项功能，丰富用户的使用选择，我们希望能够集成更多技术提供方，如 Sia。你可能需要解决：创建帮助用户解决支付储存费用的微服务，具体可以参考我们之前和 Arweave 的合作相关。Sia 团队的官方引导会在此悬赏中直接列出。

***

**资源：**

[https://sia.tech/docs/](https://sia.tech/docs/ "https://sia.tech/docs/")

**3. 将 CDN 加速文件存储与分享功能**

[https://github.com/DimensionDev/Maskbook/issues/2160](https://github.com/DimensionDev/Maskbook/issues/2160 "https://github.com/DimensionDev/Maskbook/issues/2160")

**平台：Gitcoin**

**经验要求：中级**

**类别：Mask 插件**

**时限：2 周**

**悬赏金额：500 DAI**

**需求描述：**

目前，Mask Network 的文件存储与分享功能由去中心化储存协议 Arweave 提供后端支持，用户能够自由上传或下载文件。但诸多因素都可能影响着端点的稳定性，所以我们希望能够接入 CDN 以为全球用户改善该功能的使用体验。

在未来，我们正计划添加更多的 “后端”，并同样希望能够接入 CDN。

**资源：**

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService](https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService "https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService")

***

**4. 允许 Twitter 个人资料页封面图替换成任意媒体形式**

[https://github.com/DimensionDev/Maskbook/issues/2236](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

**平台：Gitcoin**

**经验要求：中级**

**类别：Mask 插件**

**时限：2 周**

**悬赏金额：1000 DAI**

**需求描述：**

受 Twitter 用户 @Prathkum 启发，我们想要为 Mask Network 用户提供自定义 Twitter 封面图为任意媒体形式的功能，诸如 GIF、视频、甚至任意 H5 页面。我们仍希望你能提供独立的解决方案，虽然我对此已经有了想法。请在这里提出你的个人意见，我会在最后和你分享我的想法。

**资源：**

[https://github.com/DimensionDev/Holoflows-Kit](https://github.com/DimensionDev/Holoflows-Kit "https://github.com/DimensionDev/Holoflows-Kit")

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins](https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins "https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins")

[https://github.com/DimensionDev/Stego-JS](https://github.com/DimensionDev/Stego-JS "https://github.com/DimensionDev/Stego-JS")

***

**5. 将 Incognito 以插件形式接入 Mask Network 以实现私密直接转账**

[https://github.com/DimensionDev/Maskbook/issues/2068](https://github.com/DimensionDev/Maskbook/issues/2068 "https://github.com/DimensionDev/Maskbook/issues/2068")

**平台：Gitcoin**

**经验要求：中级**

**类别：Mask 插件**

**时限：4 周**

**悬赏金额：1000 DAI**

**需求描述：**

该赏金希望将 [https://incognito.org/](https://incognito.org/ "https://incognito.org/") 以插件形式接入 Mask Network，用户可以隐藏（shield）并直接交易 ETH 以及其他加密货币。我们想要寻找在 UI 以及如何调用该插件方面更为开放的想法，如：在浏览 Twitter 页面时，当鼠标悬停于 $PRV，会有带有 pDEX 的弹窗显示。希望大家能提供更多的想法。

这是一则联合悬赏，由 Incognito 团队以及 Mask Network 团队共同发布，Incognito 团队将会提供官方帮助。

**资源：**

[https://we.incognito.org/t/prv-holders-presentation-november-2020/8135](https://we.incognito.org/t/prv-holders-presentation-november-2020/8135 "https://we.incognito.org/t/prv-holders-presentation-november-2020/8135")

[https://ethresear.ch/t/incognito-mode-for-ethereum/6232](https://ethresear.ch/t/incognito-mode-for-ethereum/6232 "https://ethresear.ch/t/incognito-mode-for-ethereum/6232")

[https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf](https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf "https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf")

[https://incscan.io/](https://incscan.io/ "https://incscan.io/")

[http://docs.incognito.org/](http://docs.incognito.org/ "http://docs.incognito.org/")

**6. 拓展在 Twitter 上的图片隐写功能**

[https://github.com/DimensionDev/Maskbook/issues/1947](https://github.com/DimensionDev/Maskbook/issues/1947 "https://github.com/DimensionDev/Maskbook/issues/1947")

**平台：Gitcoin**

**经验要求：中级**

**类别：Mask 核心功能**

**时限：2 周**

**悬赏金额：500 DAI**

**需求描述：**

我们希望能够拓展在 Twitter 上的图片隐写功能（[https://github.com/DimensionDev/Maskbook/issues/1217](https://github.com/DimensionDev/Maskbook/issues/1217 "https://github.com/DimensionDev/Maskbook/issues/1217")），使用户也能够发送加密图片。由于上一则悬赏是在去年 7 月完成的，我们的代码库存在较大变动，所以还需要你完成一些 rebase 的工作。

**资源：**

[https://github.com/DimensionDev/Maskbook/pull/1338](https://github.com/DimensionDev/Maskbook/pull/1338 "https://github.com/DimensionDev/Maskbook/pull/1338")

[https://github.com/DimensionDev/Maskbook/pull/1352](https://github.com/DimensionDev/Maskbook/pull/1352 "https://github.com/DimensionDev/Maskbook/pull/1352")

[https://www.youtube.com/watch?v=JzvILdOPN3A](https://www.youtube.com/watch?v=JzvILdOPN3A "https://www.youtube.com/watch?v=JzvILdOPN3A") 由我们的社区开发者 @nazariyv 录制的演示视频也可提供参考。

**7. 线上活动报名注册**

[https://github.com/DimensionDev/Maskbook/issues/1892](https://github.com/DimensionDev/Maskbook/issues/1892 "https://github.com/DimensionDev/Maskbook/issues/1892")

**类别：Mask 插件**

**背景及介绍：**

当前，许多活动都需要借助社交网络平台来传播并吸引受众参与。然而 Twitter 目前还不支持将活动包含在单一推文中发送。我们仅能在帖子中分享某个 eventbrite 链接，再邀请他人点击该链接。这样的做法效率较低，我们希望能够解决这一问题。

**问题描述：**

我们希望参与者能够事先了解 Facebook 活动是如何运作的，如：[https://www.facebook.com/events/718053602385449.](https://www.facebook.com/events/718053602385449. "https://www.facebook.com/events/718053602385449.") 我们并不想要完全复刻 Facebook 的 UI 设计，具体要求如下：

1\. 活动名称

2\. 活动地点（可以是包含 URL 的虚拟活动）

3\. 活动描述

4\. 参加人数

5\. 费用（可以是 0；加密货币支付为为必须项，法币为可选项）

6\. 参加要求（如：账号需有至少一次的转账记录）

7\. 已报名的参加者（地址及其他信息）

**8. Subscan 优化**

[https://github.com/DimensionDev/Maskbook/issues/1724](https://github.com/DimensionDev/Maskbook/issues/1724 "https://github.com/DimensionDev/Maskbook/issues/1724")

**时限：TBD**

**背景及介绍：**

当前，Mask Network 已成功接入行情交易插件，该插件会在用户在浏览 Twitter 页面时，将鼠标悬停于 “$” 开头的通证符号时显示。显示内容包括价格、行情趋势，且当识别到交易对时弹出 Uniswap 界面进行交易。

Subscan 是波卡生态项目中的一个浏览器，就像以太坊上的 Etherscan。除此之外，Subscan 还支持在波卡生态中的多条平行链，所以它的 UI 设计会稍稍区别于 Etherscan。我们相信这能为 Mask Network 的用户提供更多波卡项目的相关信息。

**任务需求：**

**1. Subscan API 整合**

接入 Subscan API 以获取波卡生态项目的相关信息。

**2. 交易插件方面更多的 UI 设计**

在行情交易页面中，当识别到波卡项目后能够获取更多的信息展示（TBD）。该功能可以进一步帮助用户了解项目信息以及整个波卡生态。我们认为这同样也能吸引到用户更多地在 Twitter 上讨论波卡。
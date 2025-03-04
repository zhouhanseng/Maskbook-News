---
layout: post
date: 2019-11-17
lang: zh-Hans
template: Simplified Chinese
event_date: 2019-11-17
timezone: 8
type: 回顾
tags: []
en: []
zh-Hant: []
title: Web全栈大会：EhancedPrivacywithDecentralizedIdentity
location: 成都
image: ''

---
2019年11月17日，Dimension受邀参加了2019成都Web全栈大会，JackWorks（Dimension现代前端魔法使）在全栈大会上发表了“**EnhancedPrivacywithDecentralizedIdentity**”的演讲，向前来现场的程序员小哥哥，小姐姐们从技术角度讲解了Maskbook的技术原理。

![]({{ site.baseurl_root }}/uploads/10.1.jpg)

![]({{ site.baseurl_root }}/uploads/10.2.jpg)**JackWorks**

![]({{ site.baseurl_root }}/uploads/10.3.jpg)

![]({{ site.baseurl_root }}/uploads/10.4.jpg)

![]({{ site.baseurl_root }}/uploads/10.5.jpg)**大会精彩片段**

**Maskbook简介**

Maskbook是一个浏览器插件，可以让用户在正常使用Facebook、Twitter等社交网络的情况下，保护用户的个人隐私。为此，Maskbook使用了密码学原理（对称加密和非对称加密），帮助Maskbook的用户对他们的数据进行加密处理，避免大平台滥用用户的数据隐私以达到盈利的目的。同时使用了许多前端技术来确保去中心化和隐私安全，包括了GunDB（一个去中心化图数据库），@holoflows/kit（一个自己造的浏览器扩展开发工具包）、ShadowRoot（Web标准）。

Maskbook是由Dimension公司开发的开源浏览器插件，是不受政府，组织控制的。当初想要开发Maskbook的原因是因为Facebook窃取用户数据，贩卖数据以达到谋取利润的目的，更甚的是利用这些数据影响政治，操控大选。所以Dimension想在Facebook上添加一层，用科技手段来组织头部的互联网企业滥用用户隐私，将数据的控制权回归于用户自己。当然Maskbook的使用者也无需担心开发人员会在背后使用用户的数据隐私，整个开发的过程也是透明公开的。

详情可以点击以下连结来review代码：

[**https://github.com/DimensionDev/Maskbook**](https://github.com/DimensionDev/Maskbook "https://github.com/DimensionDev/Maskbook")

![]({{ site.baseurl_root }}/uploads/10.6.jpg)

**Maskbook页面一览**

**Maskbook的原理**

Maskbook使用了对称加密和非对称加密的组合。在图中可以看到，比如Alice在Facebook上创建了一条post，在Maskbook使用过程中，每一条post都由一个AESkey用来加密，最后呈现在Facebook主页上的就是一段加密的文字。每一个AESkey都由ECDH加密给指定的接收人，最后在GunDB中同步。

![]({{ site.baseurl_root }}/uploads/10.7.jpg)

注：ECDH(EllipticCurveDiffieHellman)是一种能够让拥有各自的椭圆曲线私钥并知道对方公钥的两方在不安全通道中计算出同一个密文的方法。

**Maskbook的设计原则**

**Maskbook有三大设计原则，既：**

* **不依赖平台API**
* **无中心化服务**
* **注入DOM时信息0泄露**

前文中有说到，Maskbook产生的原因是因为想要抵制互联网巨头滥用用户数据达到盈利的行为，所以Maskbook设计的目的就是能够保护用户的数据隐私。所以在设计之初就坚定了三项设计原则以达到真正的数据保护的目的。

在成都Web全栈大会上，Jack还向到场的观众演示了了前端技术的操作和原理，我们也将他的分享内容贴出来以便大家观看。

PPT内容截图

![]({{ site.baseurl_root }}/uploads/10.8.jpg)

![]({{ site.baseurl_root }}/uploads/10.9.jpg)

![]({{ site.baseurl_root }}/uploads/10.10.jpg)

![]({{ site.baseurl_root }}/uploads/10.11.jpg)

![]({{ site.baseurl_root }}/uploads/10.12.jpg)

![]({{ site.baseurl_root }}/uploads/10.13.jpg)

![]({{ site.baseurl_root }}/uploads/10.14.jpg)

![]({{ site.baseurl_root }}/uploads/10.15.jpg)

![]({{ site.baseurl_root }}/uploads/10.16.jpg)

![]({{ site.baseurl_root }}/uploads/10,17.jpg)

![]({{ site.baseurl_root }}/uploads/10.18.jpg)

![]({{ site.baseurl_root }}/uploads/10.19.jpg)

![]({{ site.baseurl_root }}/uploads/10.20.jpg)

![]({{ site.baseurl_root }}/uploads/10.21.jpg)
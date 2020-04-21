---
layout: post
lang: en
template: English
date: 2019-11-17
timezone: 8
type: ''
tags: []
zh-cn: []
zh-tw: []
title: Chengdu Web Full Stack Conference 2019
location: Chengdu
image: ''
zh-Hans: ''
zh-Hant: ''

---
On November 17, 2019, Dimension was invited to participate **_Chengdu Web Full Stack Conference 2019_**. JackWorks delivered a speech entitled **_"Enhanced Privacy with Decentralized Identity_"** at the conference. He explained the technical principles of Maskbook from a technical perspective.

![]({{ site.baseurl_root }}/uploads/10.1.jpg)![]({{ site.baseurl_root }}/uploads/10.2.jpg)**JackWorks**

![]({{ site.baseurl_root }}/uploads/10.3.jpg)![]({{ site.baseurl_root }}/uploads/10.4.jpg)![]({{ site.baseurl_root }}/uploads/10.5.jpg)**Highlights of the Conference**

**Maskbook introduction**

Maskbook is a browser plug-in that allows users to protect their privacy when they use social networks such as Facebook and Twitter. To this end, Maskbook uses cryptographic principles (symmetric encryption and asymmetric encryption) to help users of Maskbook encrypt their data and prevent large platforms from abusing users' data privacy to achieve profitability. At the same time, many front-end technologies are used to ensure decentralization and privacy security, including GunDB (a decentralized graph database), @ holoflows / kit (a browser extension development kit made by himself), and ShadowRoot (web standard).

Maskbook is an open-source browser plug-in developed by Dimension. It is not controlled by the government or organization. The reason I wanted to develop Maskbook was that Facebook stole user data and sold it for profit, and even use this data to influence politics and manipulate elections. So Maskbook wants to add a layer on Facebook to use technology to organize head internet companies to abuse user privacy and return control of data to users themselves. Of course, users of Maskbook don't need to worry about the developers' use of user data privacy behind the scenes, and the entire development process is transparent and open.

For details, please click the following link to review the code:

[**https://github.com/DimensionDev/Maskbook**](https://github.com/DimensionDev/Maskbook "https://github.com/DimensionDev/Maskbook")

![]({{ site.baseurl_root }}/uploads/10.6.jpg)

**List of Maskbook pages**

**Maskbook Principle**

Maskbook uses a combination of symmetric and asymmetric encryption. As can be seen in the picture, for example, Alice created a post on Facebook. During the use of Maskbook, each post was encrypted by an AES key, and the last page displayed on the Facebook homepage was an encrypted text. Each AES key is encrypted by ECDH to a specified recipient and is finally synchronized in GunDB.

![]({{ site.baseurl_root }}/uploads/微信截图_20200319120313.png)

Note: ECDH (Elliptic Curve Diffie Hellman) is a method that allows two parties who have their own elliptic curve private keys and know each other's public keys to calculate the same ciphertext in an insecure channel.

**Maskbook Design Principles**

**Maskbook has three major design principles, namely:**

* **Does not rely on platform APIs**
* **Decentralized services**
* **Information leaked when DOM is injected**

As mentioned earlier, the reason for Maskbook is because it wants to resist the behavior of Internet giants abusing user data to achieve profitability, so the purpose of Maskbook is to protect user data privacy. Therefore, three design principles were firmly established at the beginning of the design to achieve the purpose of real data protection.

At the Chengdu Web Full Stack Conference, Jack also demonstrated the operation and principle of the front-end technology to the audience. We also posted his shared content for everyone to watch.

**PPT Content Screenshot**

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

**Dimension**

**Official website**

Dimension.im

**Its products**

maskbook.com

tessercube.com

**Social platform**

**Github**[https://github.com/DimensionDev](https://github.com/DimensionDev "https://github.com/DimensionDev")

**Twitter** [https://twitter.com/realmaskbook](https://twitter.com/realmaskbook "https://twitter.com/realmaskbook")

**Facebook**[https://www.facebook.com/realmaskbook/](https://www.facebook.com/realmaskbook/ "https://www.facebook.com/realmaskbook/")

**Telegram**.me/maskbook_group

Scan the following QR code to join our Telegram group \~

![]({{ site.baseurl_root }}/uploads/7.2.jpg)

活动链接：[https://web-conf.dev/#2019/](https://web-conf.dev/#2019/ "https://web-conf.dev/#2019/")
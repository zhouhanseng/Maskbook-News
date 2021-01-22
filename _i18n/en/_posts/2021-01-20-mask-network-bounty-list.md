---
layout: post
lang: en
template: English
date: 2021-01-20
timezone: 8
tags: []
ja: []
zh-Hans: []
zh-Hant: []
title: Mask Network Bounty List
description: ''
location: 上海
type: ''
image: ''

---
![]({{ site.baseurl_root }}/uploads/1-30.png)

Mask Network is an open-source project building on the existing social networks. We hope that with the collective power of our communities and developers, we could improve our codebase, nourish current functionalities, and bring a better experience to the users. For now, Mask Network has already created 10 bounties on Gitcoin — 2 completed and 8 still under development. We are expecting more developers to join us in building Mask Network, towards a new and open future Internet for all cyber citizens.

![]({{ site.baseurl_root }}/uploads/2-28.jpg)

Unfinished bounties are listed as followed. Click the links for more information.

**1: Solana and Serum in Mask Network**

[https://github.com/DimensionDev/Maskbook/issues/1722](https://github.com/DimensionDev/Maskbook/issues/1722 "https://github.com/DimensionDev/Maskbook/issues/1722")

**Time Commitment：TBD**

**Part 1: Introduction and Background**

Mask Network is designed and developed as a chain agnostic tool, which relies on no chains and in another word, supports all the chains. Currently, Mask Network is focusing on DAPPs on Ethereum but we would like to integrate more chains into our extension to provide users more options. Therefore, we are redesigning our internal wallet into a multi-chain wallet and by the time the new design is finalized, we would like to start integrating new blockchains other than Ethereum.

**Part 2: Content**

**_Solana Wallet_**

[Solana](https://solana.com/) is a scalable and high performance blockchain. We would like to integrate their wallet creation, management and support relevant on-chain operations. Wallet integration is considered as the phase two of this bounty and we are expecting this to start once we release our wallet standard.

**_Serum UI Integration_**

[Serum](https://projectserum.com/) is a decentralized on-chain trading platform which supports both orderbook and swap. We would like to integrate its interface in our [trader plugin](https://github.com/DimensionDev/Maskbook/tree/master/src/plugins/Trader). It allows users to hover their mouse on any token hashtag starting with “$” on Twitter to view its price, trending and a Uniswap exchange interface if there is a pair. Integrating Serum, we can support more options other than Uniswap so that users could directly trade tokens with Solana without leaving Twitter. This is considered the phase two.

**2: Adding Sia Network as Another Provider for the File Service**

[https://github.com/DimensionDev/Maskbook/issues/2069](https://github.com/DimensionDev/Maskbook/issues/2069 "https://github.com/DimensionDev/Maskbook/issues/2069")

**_Platform：_**_Gitcoin_

**_Experience：_**_Intermediate_

**_Category：_**_Mask Plugin_

**_Time Commitment：_**_4 Weeks_

**_Bounty Size：_**_1000 DAI_

**Part 1: Problem Description**

We have already integrated Arweave as the provider of our file service, by which users can upload any type of file and attach it to a social network post. To extend this capability and provide more options for our users, we would like to add more providers such as Sia. You might need to figure out how to create a micro-service to help pay for user’s storage fees just like what we did with Arweave. Official help from Sia team can be directly linked in this bounty.

**Part 2: Resources**

[https://sia.tech/docs/](https://sia.tech/docs/ "https://sia.tech/docs/")

**3: Add CDN for the File Service**

[https://github.com/DimensionDev/Maskbook/issues/2160](https://github.com/DimensionDev/Maskbook/issues/2160 "https://github.com/DimensionDev/Maskbook/issues/2160")

**_Platform：_**_Gitcoin_

**_Experience：_**_Intermediate_

**_Category：_**_Mask Plugin_

**_Time Commitment：_**_2 Weeks_

**_Bounty Size：_**_500 DAI_

**Part 1: Problem Description**

Right now we are using Arweave as the “backend” of the file service, where users are able to upload files onto or download from. However, the endpoint is not stable as it might be influenced by a few factors. We would like to add a CDN to help improve this experience for our users all over the world.

In the future, we are planning to add more “backends”([https://github.com/DimensionDev/Maskbook/issues/2069](https://github.com/DimensionDev/Maskbook/issues/2069 "https://github.com/DimensionDev/Maskbook/issues/2069")) and would appreciate the CDN as well.

**Part 2: Resources**

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService](https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService "https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService")

**4: Replace Twitter Profile Header Photo with any Media Type**

[https://github.com/DimensionDev/Maskbook/issues/2236](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

**_Platform：_**_Gitcoin_

**_Experience：_**_Intermediate_

**_Category：_**_Mask Plugin_

**_Time Commitment：_**_2 Weeks_

**_Bounty Size：_**_1000 DAI_

**Part 1: Problem Description**

Inspired by Twitter user [@Prathkum](https://twitter.com/Prathkum/status/1345041164605513728), I think it’s worth adding something similar to our Mask Network users by enabling decorating your Twitter header with any media type, e.g., a gif, a video or even an html5 page. We would like you to explore a possible solution yourself, although I do have an idea in my mind. Please propose your idea here and I will share my thoughts with you in the end.

**Part 2: Resources**

[https://github.com/DimensionDev/Holoflows-Kit](https://github.com/DimensionDev/Holoflows-Kit "https://github.com/DimensionDev/Holoflows-Kit")

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins](https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins "https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins")

[https://github.com/DimensionDev/Stego-JS](https://github.com/DimensionDev/Stego-JS "https://github.com/DimensionDev/Stego-JS")

**5: Integrate Incognito as a Plugin That Enables Private Direct Transfer**

[https://github.com/DimensionDev/Maskbook/issues/2068](https://github.com/DimensionDev/Maskbook/issues/2068 "https://github.com/DimensionDev/Maskbook/issues/2068")

**_Platform：_**_Gitcoin_

**_Experience：_**_Intermediate_

**_Category：_**_Mask Plugin_

**_Time Commitment：_**_4 Weeks_

**_Bounty Size：_**_1000 DAI_

**Part 1: Problem Description**

This bounty aims to integrate [https://incognito.org/](https://incognito.org/ "https://incognito.org/") as a plugin in Mask Network extension that users can shield and directly send ETH and other supported blockchains. We are looking for open ideas on the UI and how this plugin is invoked, e.g. when the mouse hovers on $PRV on Twitter, a popup window will show up with the Dex interface in it. Any idea is welcomed though.

This is a joint bounty with the Incognito team and official help from Incognito team will be offered.

**Part 2: Resources**

[https://we.incognito.org/t/prv-holders-presentation-november-2020/8135](https://we.incognito.org/t/prv-holders-presentation-november-2020/8135 "https://we.incognito.org/t/prv-holders-presentation-november-2020/8135")

[https://ethresear.ch/t/incognito-mode-for-ethereum/6232](https://ethresear.ch/t/incognito-mode-for-ethereum/6232 "https://ethresear.ch/t/incognito-mode-for-ethereum/6232")

[https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf](https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf "https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf")

[https://incscan.io/](https://incscan.io/ "https://incscan.io/")

[http://docs.incognito.org/](http://docs.incognito.org/ "http://docs.incognito.org/")

**6: Extend Image Encryption in Twitter**

[https://github.com/DimensionDev/Maskbook/issues/1947](https://github.com/DimensionDev/Maskbook/issues/1947 "https://github.com/DimensionDev/Maskbook/issues/1947")

**_Platform：_**_Gitcoin_

**_Experience：_**_Intermediate_

**_Category：_**_Mask Core Feature_

**_Time Commitment：_**_2 Weeks_

**_Bounty Size：_**_500 DAI_

**Part 1: Problem Description**

We would like to extend the image encryption functionality described in [#1217](https://github.com/DimensionDev/Maskbook/issues/1217) ([https://github.com/DimensionDev/Maskbook/issues/1217](https://github.com/DimensionDev/Maskbook/issues/1217 "https://github.com/DimensionDev/Maskbook/issues/1217")) to Twitter so that users would also be able to tweet “encryption”(pixel-level shuffled) images. Some rebase jobs also need to be done since our codebase has changed a lot since the previous bounty was finished in July.

**Part 2: Resources**

You can refer to [#1338](https://github.com/DimensionDev/Maskbook/pull/1338)([https://github.com/DimensionDev/Maskbook/pull/1338](https://github.com/DimensionDev/Maskbook/pull/1338 "https://github.com/DimensionDev/Maskbook/pull/1338")) and [#1352](https://github.com/DimensionDev/Maskbook/pull/1352)([https://github.com/DimensionDev/Maskbook/pull/1352](https://github.com/DimensionDev/Maskbook/pull/1352 "https://github.com/DimensionDev/Maskbook/pull/1352")) on the implementation. [https://www.youtube.com/watch?v=JzvILdOPN3A](https://www.youtube.com/watch?v=JzvILdOPN3A "https://www.youtube.com/watch?v=JzvILdOPN3A") would also be helpful since our great community developer [@nazariyv](https://github.com/nazariyv) filmed a great video on how it works.

**7: Online Event Registration Plugin**

[https://github.com/DimensionDev/Maskbook/issues/1892](https://github.com/DimensionDev/Maskbook/issues/1892 "https://github.com/DimensionDev/Maskbook/issues/1892")

**_Category：_**_Mask Plugin_

**Part 1: Introduction and Background**

Many events are relying on social networks to spread and attract more users. However, Twitter does not support enclosing an event into a single post. All we can do is to share an eventbrite link in the tweet and let the others click on the links themselves. This is inefficient and we are aiming to solve this problem.

**Part 2: Problem Description**

We would like any participant to take a look at how Facebook event works, e.g. [https://www.facebook.com/events/718053602385449](https://www.facebook.com/events/718053602385449 "https://www.facebook.com/events/718053602385449"). We are not expecting a complete replication of a Facebook UI. We only require the following info:

1. _Name_
2. _Location (could be a virtual event with an URL)_
3. _Description_
4. _Number of Attendees_
5. _Fee (could be 0; cryptocurrency payment is required, fiat is optional)_
6. _Attending Requirements (e.g. the account should have at least one transaction)_
7. _Registered Attendees (addresses and other info)_

All registrations need to be logged on chain so you may want to write your own smart contract for this.

**8: Subscan Improvement**

[https://github.com/DimensionDev/Maskbook/issues/1724](https://github.com/DimensionDev/Maskbook/issues/1724 "https://github.com/DimensionDev/Maskbook/issues/1724")

**_Time Commitment：_**_TBD_

**Part 1: Introduction and Background**

Mask Network now supports a trader plugin where token market info would display when a user hover their mouse on a token hashtag starting with “$” on Twitter. It shows the price, trending, supporting exchanges and a Uniswap interface if there exists a swapping pair. [Subscan](https://polkadot.subscan.io/) is a block explorer in Polkadot network that works like Etherscan in Ethereum. In addition, Subscan supports multiple Parachains in Polkadot network so the UI differs a little bit from Etherscan. We believe it’ll provide our users more info about Polkadot projects.

**Tasks**

**_Subscan API integration_**

Query Subscan API to get relevant information about a Polkadot project.

**_Extra UI in Trader Plugin_**

Add the support to show extra information (TBD) in the trader view when detecting if it’s a Polkadot project. This would further help users get richer information about a project and the entire Polkadot ecosystem. We believe this would also bring more incentives to the users to talk about Polkadot on Twitter.
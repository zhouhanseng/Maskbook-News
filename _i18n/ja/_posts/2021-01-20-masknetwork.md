---
layout: post
lang: en
template: Japanese
date: 2021-01-20
timezone: 9
tags: []
en: []
zh-Hans: []
zh-Hant: []
title: MaskNetwork の報奨金リスト
description: MaskNetwork の報奨金リスト
location: 'Shanghai '
type: ''
image: "{{ site.baseurl_root }}/uploads/1-30.png"

---
![]({{ site.baseurl_root }}/uploads/1-30.png)

MaskNetwork は、既存のソーシャルネットワークをベースにしたオープンソースのプロジェクトです。私たちは、コミュニティと開発者の力を結集して、コードベースや機能を改善しより良い体験をユーザーに提供できることを願っております。

現在、MaskNetwork はすでに 10 の報奨金を Gitcoin 上で作成しており、2つは完成したものの、8 つはまだ開発中です。すべてのサイバー市民のための新しく開かれた未来のインターネットに向けて、より多くの開発者の参加を期待しています。

![]({{ site.baseurl_root }}/uploads/2-28.jpg)

未完の報奨金は以下の通りです。詳細はリンクをクリックしてください。

**1：MaskNetworkのSolanaとSerum**

[https://github.com/DimensionDev/Maskbook/issues/1722](https://github.com/DimensionDev/Maskbook/issues/1722 "https://github.com/DimensionDev/Maskbook/issues/1722")

**締め切り：未定**

**第 1 部：導入と背景**

Mask Network はチェーンに依存しないツールとして設計・開発されており、チェーンに依存せず、別の言い方をすればすべてのチェーンをサポートしています。現在、Mask Network は Ethereum 上の DAPPs に焦点を当てていますが、ユーザーに多くの選択肢を提供するために、より多くのチェーンを我々の拡張機能に統合したいと考えています。そのため、内部ウォレットをマルチチェーンウォレットに再設計し、新しいデザインが確定するときには、Ethereum 以外の新しいブロックチェーンの統合を開始したいと考えています。

**第2部：内容**

**Solana Wallet**

Solana はスケーラブルで高性能なブロックチェーンです。彼らのウォレット作成、管理を統合し、関連するオンチェーン運用をサポートしたいと考えています。ウォレット統合は、この報奨金のフェーズ2と考えており、ウォレット標準をリリースした時点で開始されると予想されています。

**Serum UI の統合**

Serum は、オーダーブックとスワップの両方をサポートする分散型オンチェーン取引プラットフォームです。私たちは、そのインターフェイスを私たちのトレーダープラグインに統合したいと考えています。それは、ユーザーが Twitter 上の"$"で始まる任意のトークンのハッシュタグにマウスを置くことで、その価格、トレンド、ペアがある場合は Uniswap の取引所のインターフェイスを表示することができます。 Serum を統合することで、Uniswap 以外のオプションにも対応できるようになり、ユーザーが Twitter から離れることなく Solana と直接トークンを取引できるようになりました。これが第二段階と考えられています。

**2: ファイルサービスの別のプロバイダとして Sia Network を追加する**

[https://github.com/DimensionDev/Maskbook/issues/2069](https://github.com/DimensionDev/Maskbook/issues/2069 "https://github.com/DimensionDev/Maskbook/issues/2069")

**プラットフォーム：**Gitcoin

**経験：**中級レベル

**カテゴリ：**Mask プラグイン

**締め切り：**4 週間

**報奨金：**1,000 DAI

**第 1 部：**問題の説明

我々はすでにファイルサービスのプロバイダとして Arweave を統合しており、ユーザーは任意のタイプのファイルをアップロードしてソーシャルネットワークの投稿に添付することができます。この機能を拡張し、ユーザーに多くのオプションを提供するために、私たちは Sia のようなより多くのプロバイダを追加したいと考えています。Arweave でやったのと同じように、ユーザーのストレージ料金の支払いを支援するマイクロサービスを作る方法を考える必要があるかもしれません。Siaチームからの公式ヘルプは、このバウンティで直接リンクすることができます。

**第 2 部：リソース**

[https://sia.tech/docs/](https://sia.tech/docs/ "https://sia.tech/docs/")

**3: ファイルサービスのCDN を追加**

[https://github.com/DimensionDev/Maskbook/issues/2160](https://github.com/DimensionDev/Maskbook/issues/2160 "https://github.com/DimensionDev/Maskbook/issues/2160")

**プラットフォーム：**Gitcoin

**経験：**中級レベル

**カテゴリ：**Maskプラグイン

**締め切り：**2 週間

**報奨金：**500 DAI

**第 1 回目 問題の説明**

現在、私たちはファイルサービスの「バックエンド」として Arweave を使用しています。しかし、エンドポイントはいくつかの要因に影響される可能性があるため、安定していません。私たちは、世界中のユーザーのこの経験を改善するために、CDNを追加したいと考えています。

将来的には、より多くの "バックエンド"([https://github.com/DimensionDev/Maskbook/issues/2069](https://github.com/DimensionDev/Maskbook/issues/2160 "https://github.com/DimensionDev/Maskbook/issues/2160"))を追加する予定ですので、CDNもよろしくお願いします。

**第 2 部：リソース**

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins/FileService](https://github.com/DimensionDev/Maskbook/issues/2160 "https://github.com/DimensionDev/Maskbook/issues/2160")

**4: 任意のメディアタイプと Twitter のプロフィールヘッダー写真を置き換える**

[https://github.com/DimensionDev/Maskbook/issues/2236](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

**プラットフォーム：**Gitcoin

**経験：**中級レベル

**カテゴリ：**Mask プラグイン

**締め切り：**2 週間

**報奨金：**1,000 DAI

**第 1 回目 問題の説明**

Twitter ユーザーの@Prathkum さんに触発されて、Twitter のヘッダーを任意のメディアタイプ、例えばGIF、ビデオ、あるいは html5 ページで装飾できるようにすることで、MaskNetwork のユーザーにも似たようなものを追加する価値があると思います。私の頭の中にはアイデアがありますが、可能性のある解決策をご自身で探っていただきたいと思います。ここではあなたのアイデアを提案してください。

**第 2 部：リソース**

[https://github.com/DimensionDev/Holoflows-Kit](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

[https://github.com/DimensionDev/Maskbook/tree/master/packages/maskbook/src/plugins](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

[https://github.com/DimensionDev/Stego-JS](https://github.com/DimensionDev/Maskbook/issues/2236 "https://github.com/DimensionDev/Maskbook/issues/2236")

**5: プライベートな直接転送を可能にするプラグインとして Incognito を統合する**

[https://github.com/DimensionDev/Maskbook/issues/2068](https://github.com/DimensionDev/Maskbook/issues/2068 "https://github.com/DimensionDev/Maskbook/issues/2068")

**プラットフォーム：**Gitcoin

**経験：**中級レベル

**カテゴリ：**Mask プラグイン

**締め切り：**4 週間

**報奨金：**1,000 DAI

**第 1 回目 問題の説明**

この懸賞金は、[https://incognito.org/](https://incognito.org/ "https://incognito.org/") を Mask Network 拡張機能のプラグインとして統合し、ユーザーが ETH やその他のサポートされているブロックチェーンをシールドして直接送信できるようにすることを目指しています。例えば、Twitter 上の $PRV の上にマウスを置くと、 DEX インターフェイスのポップアップウィンドウが表示されます。どんなアイデアでも歓迎します。

これは Incognito チームとの共同報償であり、Incognito チームからの公式なヘルプが提供されます。

**第 2 部：リソース**

[https://we.incognito.org/t/prv-holders-presentation-november-2020/8135](https://we.incognito.org/t/prv-holders-presentation-november-2020/8135 "https://we.incognito.org/t/prv-holders-presentation-november-2020/8135")

[https://ethresear.ch/t/incognito-mode-for-ethereum/6232](https://ethresear.ch/t/incognito-mode-for-ethereum/6232 "https://ethresear.ch/t/incognito-mode-for-ethereum/6232")

[https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf](https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf "https://medium.com/incognito-chain/incognito-mode-for-ethereum-e0bbae096eaf")

[https://incscan.io/](https://incscan.io/ "https://incscan.io/")

[http://docs.incognito.org/](http://docs.incognito.org/ "http://docs.incognito.org/")

**6：Twitter で画像の暗号化を拡張する**

[https://github.com/DimensionDev/Maskbook/issues/1947](https://github.com/DimensionDev/Maskbook/issues/1947 "https://github.com/DimensionDev/Maskbook/issues/1947")

**プラットフォーム：**Gitcoin

**経験：**中級レベル

**カテゴリ：**Mask コア機能

**締め切り：**2 週間

**バウンティサイズ：**500 DAI

**第 1 部： 問題の説明**

\#1217 ([https://github.com/DimensionDev/Maskbook/issues/1217](https://github.com/DimensionDev/Maskbook/issues/1217 "https://github.com/DimensionDev/Maskbook/issues/1217")) で説明した画像の暗号化機能を Twitter にも拡張して、ユーザーが「暗号化」(ピクセルレベルのシャッフル)画像をツイートできるようにしたいと思います。前回の報奨金が7月に終了してからコードベースが大きく変わったので、いくつかのリベース作業も行う必要があります。

**パート2: リソース**

[https://www.youtube.com/watch?v=JzvILdOPN3A](https://www.youtube.com/watch?v=JzvILdOPN3A "https://www.youtube.com/watch?v=JzvILdOPN3A") は、私たちの素晴らしいコミュニティ開発者である @nazariyv さんが、どのように動作するかについての素晴らしいビデオを撮影してくれたので、参考になるでしょう。

**7: オンラインイベント登録プラグイン**

[https://github.com/DimensionDev/Maskbook/issues/1892](https://github.com/DimensionDev/Maskbook/issues/1892 "https://github.com/DimensionDev/Maskbook/issues/1892")

**カテゴリ：Mask プラグイン**

**第 1 部：導入と背景**

多くのイベントでは、SNS に頼って拡散し、より多くのユーザーを獲得しています。しかし、Twitter はイベントを 1 つの投稿に囲い込むことには対応していません。ツイートの中に eventbrite のリンクを入れて共有し、他の人が自分でリンクをクリックするようにすることしかできません。これは非効率的であり、この問題の解決を目指しています。

**第 2 部：問題点の説明**

参加される方には、Facebook イベントの仕組みを見ていただきたいと思います。[https://www.facebook.com/events/718053602385449](https://www.facebook.com/events/718053602385449 "https://www.facebook.com/events/718053602385449") など。Facebook UI の完全な複製は期待していません。必要なのは以下の情報のみです。

名前

場所 (URL 付きの仮想イベントになる可能性があります)

説明

出席者数

手数料（0 の場合もあります。暗号資産の支払いが必要です。

出席条件（例：口座の取引が1回以上あること)

登録されている参加者（住所や他の情報)

すべての登録はチェーンでログを取る必要があるので、そのために自分でスマートコントラクトを書いたほうがいいかもしれません。

**8: Subscan の改善**

[https://github.com/DimensionDev/Maskbook/issues/1724](https://github.com/DimensionDev/Maskbook/issues/1724 "https://github.com/DimensionDev/Maskbook/issues/1724")

**締め切り：未定**

**第 1 部：導入と背景**

Mask Network は、ユーザーが Twitter の"$"で始まるトークンのハッシュタグにマウスを合わせると、トークンのマーケット情報が表示されるトレーダープラグインをサポートしています。これは、価格、トレンド、サポートされている取引所とUniswap インターフェイスを示しています。Subscanは、Ethereum の Etherscan のように動作する Polkadot ネットワークのブロックエクスプローラーです。また、Subscan は Polkadot ネットワークで複数の Parachains をサポートしているので、Etherscan とは少しUIが異なります。ユーザーに Polkadot プロジェクトの情報をより多く提供できるようになると思います。

**タスク**

**SubscanAPI 統合**

Polkadot プロジェクトに関連する情報を取得するための Subscan API を実行します。

**トレーダープラグインの追加UI**

Polkadot プロジェクトかどうかを検出する際に、トレーダービューに追加情報を表示する機能を追加しました。これにより、ユーザーはプロジェクトや Polkadot エコシステム全体についてより豊富な情報を得ることができるようになります。また、ユーザーが Twitter で Polkadot について話すことで、より多くのインセンティブが得られると考えています。
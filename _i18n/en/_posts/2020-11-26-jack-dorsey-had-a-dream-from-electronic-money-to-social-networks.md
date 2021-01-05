---
layout: post
lang: en
template: English
date: 2020-11-26
timezone: 8
tags: []
zh-Hans: []
zh-Hant: []
title: 'Jack Dorsey Had a Dream: From Electronic Money to Social Networks'
location: 上海
type: ''
image: ''

---
_This article is written by Orange Paper(橙皮书) and translated by_ [Tianyu M. Fang](https://medium.com/u/e2edf20aad19?source=post_page-----307fc849c860--------------------------------)_. The Mask Network team supported the translation as well. In our perspective, it’s a bold step of Twitter to announce its plan of decentralization last December, though we haven’t heard any news since then. It’s a long term effort to build the portal to the new Internet on top of existing platforms, and Mask Network would like to facilitate this journey._

**If Bitcoin had existed before Twitter, would the history of social networking have been rewritten?**

[1-jpeg.crdownload]({{ site.baseurl_root }}/uploads/1-jpeg.crdownload "1-jpeg.crdownload")

(This story is completely fictional.)

One night in 2007, Jack Dorsey had a dream.

Jack had been a child who was used to being alone. While other kids were playing American football, he was busy obsessing over maps and train sounds. Train operators and dispatchers communicating their geographic locations over the radio had a special charm for him. These messages were simple but efficient: Where are they going? Doing what? Where are they now?

Years later, the child created a product called Twitter. The idea of a _tweet_ — a bird call characterized by short, frequent, and fast sounds — is a manifestation of simple, efficient communication. It was an idea inadvertently inspired by his study of trains as a child.

It was June 2007, just over a year after Twitter’s launch. Three months earlier, at the SXSW in Texas, Twitter had won the Web Award in the “blog” category, and the number of registered users had risen steadily, first to 100,000 and then, three months later, to 250,000. The office was abuzz with excitement.

Jack was on the edge of his seat, staring at his phone and wondering what to tweet. To make it easier for people to use Twitter via SMS, the team had just added a somewhat odd feature to the product in February — a 140-character limit. The messages were becoming shorter, but they were traveling faster than ever.

He suddenly remembered a post he had seen the other day that mentioned something called _Bitcoin_. The author was Satoshi Nakamoto; he was supposed to publish a paper on it in 2008, but he eventually started to write the code for it a year earlier.

_A protocol for electronic money_? Jack didn’t quite understand what that meant, but he had a vague feeling that it would be something interesting.

The night when he got home from work, Jack had a strange nightmare. He dreamed that Twitter had become a hit. As users were growing faster, the company’s technical capabilities were failing — the product was often down. The team was busy developing new features while the management struggled with problems. The relationship among partners was worsening, and the CEO battle in the office resembled an internal courtroom drama.

But that was not the worst of it — the worst was that Twitter would become one of the largest social networks in the world. With its growing number of users, political manipulation, cyber violence, bot accounts, and hate speech, Twitter was filled with a stream of vulgar, eye-popping messages.

Worse yet, when the team tried to do something about the hostility on the platform, users complained that Twitter was over-regulating their speech. When the team tried to leave it alone, governments and the law obliged them to intervene. Twitter went public, but the product was anything but what Jack had wanted.

The next day at work, Jack told his partner Evan Williams about his nightmare last night. The nightmare was weighing on his mind a bit, and in order to keep Twitter from ending up like this, he told Evan, maybe we should make Twitter more open, not as a product, but as a _protocol_. Like TCP/IP. Anyone can develop a new product on it — that’s a liberation for the team.

_But isn’t that what we’re doing now?_ Evan didn’t quite understand Jack’s thinking. In his opinion, Twitter was already open enough that all APIs used by the product were public, and any developer could call the data on the platform at will. In the future, there would even be different Twitter clients for users to choose from. What’s the point of making it a protocol when we already have an open API?

“The difference,” Jack continued, “is that if Twitter goes public in the future, we’ll have to stop the API and block all other clients so we can capture the most users to squeeze profit. If we make a decentralized protocol, we will not be able to stop people from developing applications on top of the protocol, because the protocol will not be owned by anyone. At the same time, we’ll have nothing to do with the user behaviors on the platform or the content regulation policies it needs to comply with.”

“Social networking can be like emails. They follow the same set of standards, including the SMTP and IAMP protocols. For example, even if I use Yahoo Mail, I’ll be able to communicate with Gmail users.”

“If someone makes a new product using the same protocol, that product will be compatible with Gmail from day one. Moreover, the protocol is standardized so that you can unconditionally download, delete, or transfer your own mail data on the Gmail platform — users will be able to migrate at virtually no cost.”

“This way, whenever a new product enters the market, it won’t face an absolute monopoly against the existing giant players, because users can always take their data and migrate to the new product. In other words, the market will always remain open.”

“What will it be like to build a decentralized protocol for social networking? Imagine this — “

“The Simple Social Network Protocol, or SSNP, creates a model for a Twitter-like social network. It offers standards for account registration, data storage, and migration, as well as basic features such as tweeting, retweeting, commenting, following, or liking a tweet.”

“If a product is built under SSNP, then it naturally interoperates with other SSNP protocol products. What is the concept of interoperability in this context?”

“For example, the Facebook user _john@facebook.com_ can tag the Twitter user _jane@twitter.com_. Users on one platform can receive messages from their contact on another platform. They’ll be able to follow each other and reply to each other’s posts.”

Facebook and Twitter might have their own content censorship policies, their own rules of speech, their own community culture, and user clients with different functional designs and UIs. If John wants to migrate to Mastodon, the migration cost will be very low — he will export the data, take his followers with him, and continue his life on the new platform as _john@mastodon.cloud_.

The whole office fell silent after Jack’s presentation. Obviously, this “protocols not platforms” approach is much closer to what Twitter looked like when it was created, and it’s a model the team would have preferred.

But at the same time, one of the most important questions remained unanswered:

Twitter is a commercial community. Developing protocols doesn’t make money. How do we keep the team running in the long run? Sure, we’re in early rounds of funding and don’t really need to think about the business model — but sooner or later investors will liquidate or exit. An open-source protocol that doesn’t monopolize user data and their social relationships will have a hard time extracting value.

Jack also didn’t have an answer to this question. He’s thought about it, but nothing good has come out yet. This was the last hurdle that seemed insoluble.

Suddenly, one word flashed in his mind: Bitcoin.

Satoshi Nakamoto was developing a similar network. It wasn’t a social network, however, but a payment network.

Bitcoin is a peer-to-peer electronic payment network that allows anyone to transfer money to another person in the world, without a company or intermediary. The overhead cost of this payment system is borne by the P2P nodes in the network — also known as miners, who earn rewards by protecting the network. These rewards are the Bitcoins automatically distributed by the system.

When more people use the Bitcoin network, the rewards become more valuable. The founding team that developed the protocol, as well as the first nodes to join the Bitcoin network, could theoretically obtain a large number of Bitcoins relatively cheaply in the early stages, and then be rewarded even more when the network becomes more valuable. In this way, Bitcoin solves the business model problem while developing a decentralized protocol.

Why, then, can’t we use the same approach to develop a social media protocol? After all, electronic money and social networking seem to be necessities and public utilities of human society. It is difficult to commercialize, but at the same time it needs to serve a public social function.

The office was still silent, and Jack didn’t have time to tell everyone what he was thinking. He had to make sure that his understanding of Bitcoin was correct. He was thinking that maybe he should talk to this Satoshi Nakamoto first.

All in all, the future of Twitter was still very murky. But Jack had at least some kind of answer in mind.

He was also thinking that maybe he should make another product besides Twitter — after all, Bitcoin is just getting started. There is a question mark over the success of a decentralized electronic currency. Maybe he should start with a centralized payment product, called Square, to solve the problem of people receiving money and paying for it. If this product comes to fruition, he’d be happy to help Satoshi in turn by funding the development of this Bitcoin project — which, of course, would come later.

(The end.)

A few final words.

1\. Jack Dorsey, the CEO of Twitter, [announced](https://twitter.com/bluesky/status/1204766347512537088) that the company will fund a small team of 5 people, with the participation of the Twitter CTO himself, to develop a decentralized social networking protocol, and Twitter will be one of the clients that meets the criteria of this protocol.

This team, called Bluesky, will have a lot of freedom and autonomy. They can build upon the existing work on Twitter, or if can start something else if they feel the need to do so.

2\. [@jack](https://twitter.com/jack/status/1204766078468911106) said that this decision was made because he realized that there are some things that are difficult to achieve with a centralized platform. For Twitter, these things include:

First, a set of globally accepted censorship policies for content on social networks. In practice, legal requirements and community culture vary from region to region. It is not possible to create a universal set of standards.

Second, recommendation algorithms themselves are not open source, so users do not have the freedom of choice.

Thirdly, social media platforms, in their own self-interest, will naturally push eye-catching and clickbait-y contents.

New technologies have made decentralization possible. Blockchain provides an open and sustainable data storage strategy as well as governance and monetization mechanisms.

3\. USV investor Fred Willson retweeted Jack’s tweet, giving approval to his decision. He said that the early Twitter took a path closer to a decentralized protocol, with open APIs and many third-party clients, but then the team decided that they wanted to take a more centralized path.

At that time this was absolutely the right decision for a commercial company in. But Fred sometimes wonders if Twitter had come after Bitcoin, rather than before, maybe the outcome would have been different.

4\. Jack holds Bitcoin and only Bitcoin. His other payment company, Square, has created a program called Square Crypto to fund research related to the Bitcoin protocol.

5\. Twitter’s attempts at “decentralization” and “self-revolution” were not well received by many users. One of the reasons mentioned by many is that there are already many similar decentralized social networks, which are open source products with open protocols, but they don’t attract many users.

In our view, there are several reasons:

First, the experience of these existing decentralized social media platforms is too different from the more popular centralized ones. They are not easy to use.

Second, the existing social networking protocols have not become the _de facto_ standards, and the protocols themselves are not appealing enough to developers.

Lastly, it is difficult for new social networking platforms to take off if they are not “interoperable” with existing ones. Because Facebook, Twitter, and all the other platforms have such a strong grip on user data and relationships, the network effect is so great that it is nearly impossible for all users to migrate there. It would be a big difference if Jack, as the leader, could get this protocol to work with Twitter first.

(The end of the article. Special thanks to Orange Paper and [Tianyu M. Fang](https://medium.com/u/e2edf20aad19?source=post_page-----307fc849c860--------------------------------))
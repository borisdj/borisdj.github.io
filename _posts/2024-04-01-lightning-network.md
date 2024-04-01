---
title: "Lightning Network"
date: 2024-04-01T00:00:00-00:00
categories: [fintech]
tags: [finance, crypto]
classes: wide
excerpt: "Lightning Network"
---

**[Lightning Network](https://en.wikipedia.org/wiki/Lightning_Network){:target="_blank"} (LN) development and usecase**<br>
Bitcoin Layer 2 (L2) - [Tech behind](https://medium.com/coinmonks/the-lightning-network-technology-behind-bitcoins-scaling-solution-915c07455ca8){:target="_blank"}

![bitcoin-future](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-model.jpg)

<center>QR Link</center>
![QR Link](https://quickchart.io/qr?text=https://infopedia.io/lightning-network/)

**Scaling Issues**:  
* Bitcoin base layer and Blockchain architecture in general does not scale.  
In order to remain decentralized enough in the long term, from a governance perspective, it needs robust structure and high redundancy.  
This puts practical constraints to DB to enable many distributed nodes. It also limits the number of transactions per second (TPS), in order to achieve global sync state for consensus.  
Even if Bitcoin 10 TPS were to be somehow miraculously increased by a factor of 10 without losing security, still 100 TPS would change nothing, since for the entire world we need at least 1 million TPS.
* [**Blockchain Trilemma**](https://medium.com/@chainway_xyz/the-true-trilemma-for-bitcoin-layers-06855d535b95){:target="_blank"} <u>/\</u> (resilience vs efficiency):  
1.Decentralisation, 2.Security, 3.Scalability (num 3 left for [**next layers**](https://www.minima.global/post/taking-blockchain-scalability-to-the-next-layer){:target="_blank"}).

-- One of the most promising **Solutions** is the so-called [***Lightning Network***](https://lightning.network/){:target="_blank"}.  
It works via channels between nodes, and needs base transactions for opening, closing, rebalancing and routing.  
One simple analogy is with when you open a beer tap with bartender and at the end of night it gets settled.
With current transaction throughput we could see each year opening up to 100 000 new channels.  
Later process for onboarding users can be increased even more with [**Channel Factories**](https://bitcoinops.org/en/topics/channel-factories/){:target="_blank"} for [**scalability**](https://bitcoin.stackexchange.com/questions/67158/what-are-channel-factories-and-how-do-they-work){:target="_blank"}.  
But once set up it can handle large volumes of transactions without the need for regular main net connection, only rarely.  
-- As such it has the potential for over [**1 million**](https://cointelegraph.com/news/bitcoin-lightning-network-vs-visa-and-mastercard-how-do-they-stack-up){:target="_blank"} TPS, just the right number, while keeping the fees low.  
Still it should be mentioned that this is not necessarily the ultimate fix ([Challenges](https://www.blockchain-council.org/blockchain/what-is-the-lightning-network/){:target="_blank"} & [Response](https://murchandamus.medium.com/i-have-just-read-jonald-fyookballs-article-https-medium-com-jonaldfyookball-mathematical-fd112d13737a){:target="_blank"}).  
Those protocols are meant to extend Bitcoin's functionality up to a point, while maintaining the base layer secure and decentralized ([**LN 2.0**](https://blog.theabacus.io/lightning-network-2-0-b878b9bb356e){:target="_blank"}).  

-- Another issue that Lighting improves upon is **Privacy** as transactions are not publicly visible on the chain.  
It also adds support for miliSats a sub Sat (1/1000), with higher decimal precision for microtransactions and streaming payments.  

-- Also worth noting is that it is not currently feasible for every person on the planet to have a fully custodial lightning wallet with its own node.  
In addition, for most people this is too complicated, so it might not even be necessary.  
Instead, a more realistic approach is to have many distributed custodians, for example like today we have Wallet of Satoshi - WoS.  
-- In fact every bank could become custodian and a lightning node.  
On top of that maybe only few percent of the global population will have self custody, with either completely or partially trustless implementation.  
One example with non routing nodes is the [**Phonix**](https://phoenix.acinq.co/){:target="_blank"} wallet that has node on mobile but it only connects to the  [Acinq](https://acinq.co/){:target="_blank"} node. They provide services of automatic channel management and balancing liquidity. Phoenix is a great wallet, where you keep your keys but still is very user-friendly with trust-minimized model.  
Then there is an option for federated nodes like [**FediMint**](https://fedimint.org/){:target="_blank"} that are using federated models for governance.  

-- So in the next 20+ years if few billion people, would start using it we could expect around 50 000 nodes with average 100 K users.  
Of course there would be a small number of ones with million users and also many small ones with few hundreds users - Normal Distribution of banking, as currently there are around 25 000 [banks globally](https://www.linkedin.com/pulse/how-many-banks-globally-david-gyori){:target="_blank"}. (Mega banks vs [**Community banks**](https://www.extractable.com/insights/by-the-numbers-mega-banks-vs-community-banks/){:target="_blank"}.)  
-- Also it is expected from big corporations to have their own nodes and channels with vendors for payment, while small companies would use custodian banks.  
Just like large enterprises have their own accounting sector, while smaller ones hire external service from accounting bureaus.  

Bitcoin Lightning wallets - [**Review**](https://www.coinbureau.com/analysis/best-bitcoin-lightning-wallets/){:target="_blank"}  
![wallets](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-wallets.jpg)

Self custody lightning wallets - [**Comparison**](https://www.coindesk.com/consensus-magazine/2024/01/26/which-is-the-best-self-custody-lightning-wallet/){:target="_blank"} (tested in Africa):  
***Phoenix, Mutiny, Blixt, Green, Zeus, Wallet of Satoshi***.

In the meantime there is an interesting use case for stableSats, like dollars or even euros on top of Bitcoin network, e.g. for remittances, and particularly in the global south where many local currencies are quite unstable with very high inflation:

| Wallet | StableCoin | Based on | Org/location  |
| -----  | ---------- | -------- | ------------- |
| [**Aqua**](https://aquawallet.io/){:target="_blank"}  | USDT | [Liquid (BlockStream)](https://liquid.net/){:target="_blank"} | [Jan3](https://jan3.com/){:target="_blank"} |
| [**Blink**](https://www.blink.sv/){:target="_blank"}  | Exchange | ex Bitcoin Beach (BBW) | [Galloy](https://galoy.io/){:target="_blank"} |
| [**10101**](https://10101.finance/){:target="_blank"} | DLC (not LN) | USDp - bolt | Australia |
| [**Mutiny**](https://www.mutinywallet.com/){:target="_blank"} | DLC Channel | Web-based  | Austin TX |

Network [**Topology**](https://appliednetsci.springeropen.com/articles/10.1007/s41109-023-00602-2){:target="_blank"} (distribution of nodes):  
![graph](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-graph.jpg)

YT talks to listen:  
-[Bitcoin's Lightning Network](https://www.youtube.com/watch?v=rrr_zPmEiME){:target="_blank"} (*Simply Explained*)  
-[Bitcoin Lightning Network: Need to know](https://www.youtube.com/watch?v=J3cQNpOR_a0){:target="_blank"} (*Coin Bureau*)  
-[What is the Lightning Network?](https://www.youtube.com/watch?v=pBh4DcM-0pg){:target="_blank"} (*99Bitcoins*)  
-[What is it? why should I care?](https://www.youtube.com/watch?v=AYAreuNzx58&t=39s){:target="_blank"} & [Tech Intro to LN - devs 2020](https://www.youtube.com/watch?v=E1n3sKKPD_k){:target="_blank"} (*Andreas Antonopoulos*)  
-[Lightning Made Easy](https://www.youtube.com/watch?v=nusOl6wb1a4){:target="_blank"} & [LN wiht Phoenix](https://www.youtube.com/watch?v=9j_slmZ7Eyo) (*Bitcoin University*)  

Dashboard info:  
[mempool.space/lightning](https://mempool.space/lightning){:target="_blank"}  
[clarkmoody.com/dashboard](https://bitcoin.clarkmoody.com/dashboard/){:target="_blank"}  
[bitbo.io](https://bitbo.io/target="_blank")  

Previous Bit posts:  
B1. [**(r)Evolution of Money**](https://infopedia.io/revolution-of-money/)  
B2. [**Bitcoin future and macro outlook**](https://infopedia.io/bitcoin-future-macro-outlook/)  


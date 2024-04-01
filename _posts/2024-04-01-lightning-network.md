---
title: "Lightning network"
date: 2024-04-01T00:00:00-00:00
categories: [fintech]
tags: [finance, crypto]
classes: wide
excerpt: "Lightning Network"
---

**Lightning Network (LN) development and usecase**<br>
Bitcoin Layer 2

![bitcoin-future](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-model.jpg)

<center>QR Link</center>
![QR Link](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-qr.png)

Scaling Issues:
* Bitcoin base layer and Blockchain architecture in general does not scale.  
In order to remain decentralised enough, from governance aspect, in the long term, it needs robust structure and high redundancy.  
This puts practical constains to DB to enable many distributed nodes. It also limits number of transaction per second (TPS), in order to achive global sync state for consensus.  
Even if Bitcoin 10 TPS were to be somehow miraculously increased by a factor of 10 without losing security, still 100 TPS would change nothing, since for entire world we need at least 1 million TPS.
* In [**Blockchain Trilemma**](https://medium.com/@chainway_xyz/the-true-trilemma-for-bitcoin-layers-06855d535b95 target="_blank") (resilience vs efficiency): /__\ 1.Decentralisation, 2.Security, 3.Scalability.  
Bitcoin leaves scalability for [**next layers**](https://www.minima.global/post/taking-blockchain-scalability-to-the-next-layer target="_blank").

One of most promising solution is the so called Lightning Network.  
It works via channels betwean nodes, and needs only base net transaction for opening, closing and rebalancing.  
With current transaction throughput we could se each year opening ofup to 100 000 new channels.  
Later number of onboarded user can be increased even more with [**Channel Factories**](https://bitcoinops.org/en/topics/channel-factories/ target="_blank") for [**scalability**](https://bitcoin.stackexchange.com/questions/67158/what-are-channel-factories-and-how-do-they-work target="_blank").  
But once set up it can handle large number of transations without the need for regular main net connection, only rarely.  
As such it has the potential for over 1 million TPS, just the right number.  
Still it should be mentioned that this is not necesarily ultimate univeral fix. Those protocols are meant to extend Bitcoin's functionality up to a point, while maintaining the base layer secure and decentralized.  

Another issue that Lightng improves upon is the Privacy as transactions are not publicly visible on the chain.  
It also adds support for miliSats a sub Sat (1/1000), with higher decimal precision for microtransations and streaming payments.  

Also worth noting is that it is not curently feasible for every person on planet to have fully custodial lightnig wallet with its own node.  
In addition most people this is too complicated so it not even necessary.  
Instead more realistic aprocs is to have many distbitued custodians like today is wallet of satoshi.  
In fact every bank could become custodin and a lightning node.  
On top of that maybe 5% of global population will have self custody, either full or partial nodes.  
One example of non routing nodes is [**Phonix**](https://phoenix.acinq.co/ target="_blank") wallet that has node on mobile but it only connects to Acinq node that prvider services of chanel management and balancing liqudity.  
Then there is option for federated nodes like [**FediMint**](https://fedimint.org/ target="_blank") that uses federaion for governance.  

So in the next 20 years if 4 bilion would start using it, we could expect 50 000 nodes with average 100 K users.  
Of course there would be small number of ones with million users and also many small one with few hunders users - Normal Distribution banking scale ([The NUMBER of BANKS globally is 25 000](https://www.linkedin.com/pulse/how-many-banks-globally-david-gyori target="_blank")). 
(Mega banks vs [**Community banks**](https://www.extractable.com/insights/by-the-numbers-mega-banks-vs-community-banks/ target="_blank").)
Also we expect big coorporation to have their owns nodes and chanels with vendors for to payment, while small companies would use custodian banks.  
Just like big entrprises have their own accounting sector, while small one hire external ones from accounting burau.  

In the meantime there is an interesting usecase for stableSats, like dollars on top on Bitcoin network, for remitances and in the global south with instable local currencies:

| Wallet | StableCoin | Based on| Org/location  |
| -----  | ---------- | ------- | ------------- |
| [**Aqua**](https://aquawallet.io/ target="_blank")  | USDT | [Liquid (BlockStream)](https://liquid.net/ target="_blank") | [Jan3](https://jan3.com/ target="_blank") |
| [**Blink**](https://www.blink.sv/ target="_blank")  | Exchange | ex Bitcoin Beach (BBW) | [Galloy](https://galoy.io/ target="_blank") |
| [**10101**](https://10101.finance/ target="_blank") | DLC (not LN) | USDp - bolt | Australia |
| [**Mutiny**](https://www.mutinywallet.com/ target="_blank") | DLC Channel | Web-based  | Austin TX |

Bitcoin Lightning wallets - [**review**](https://www.coinbureau.com/analysis/best-bitcoin-lightning-wallets/ target="_blank")  
![wallets](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-wallets.jpg)

Self custody lightning wallets - [**comparison**](https://www.coindesk.com/consensus-magazine/2024/01/26/which-is-the-best-self-custody-lightning-wallet/ target="_blank") (tested in Africa):  
***Phoenix, Mutiny, Blixt, Green, Zeus, Wallet of Satoshi***.

Network [**Topology**](https://appliednetsci.springeropen.com/articles/10.1007/s41109-023-00602-2 target="_blank") (distirbuted nodes of custodians):  
![graph](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-graph.jpg)

Bit Dashboard info:  
[mempool.space/lightning](https://mempool.space/lightning target="_blank")  
[clarkmoody.com/dashboard](https://bitcoin.clarkmoody.com/dashboard/ target="_blank")  
[bitbo.io](https://bitbo.io/target="_blank")  


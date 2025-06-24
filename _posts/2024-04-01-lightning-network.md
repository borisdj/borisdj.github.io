---
title: "Lightning Network"
date: 2024-04-01T00:00:00-00:00
categories: [fintech]
tags: [finance, crypto]
classes: wide
excerpt: "Lightning Network"
---

**[LN](https://en.wikipedia.org/wiki/Lightning_Network){:target="_blank"} development and usecase**<br>
Bitcoin Layer 2 (L2) - [**Tech behind**](https://medium.com/coinmonks/the-lightning-network-technology-behind-bitcoins-scaling-solution-915c07455ca8){:target="_blank"}

LANG(jezik): Global(en-us) / [Local](https://infopedia.io/sr-latn/lightning-network/)(sr-latn)<br>

![bitcoin-future](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-model.jpg)

**Scaling Issues**:  
* Bitcoin base layer and Blockchain architecture in general do not scale.  
In order to remain decentralized enough in the long term, from a governance perspective, it needs robust structure and high redundancy.  
This puts practical constraints on DB to enable many distributed nodes. It also limits the number of transactions per second (TPS), in order to achieve global sync state for consensus. DB size needs to grow at moderate pace in order for many nodes to be able to keep up with storage capacity and internet bandwith.  
Even if Bitcoin 10 TPS were to be somehow miraculously increased by a factor of 10 without losing security, still 100 TPS would change nothing, since for the entire world we need at least 1 million TPS.
* [**Blockchain Trilemma**](https://medium.com/@chainway_xyz/the-true-trilemma-for-bitcoin-layers-06855d535b95){:target="_blank"} <u>/\</u> (resilience vs efficiency):  
1.Decentralisation, 2.Security, 3.Scalability (No̱ 3 left for [**next layers**](https://www.minima.global/post/taking-blockchain-scalability-to-the-next-layer){:target="_blank"}).

-- One of the most promising **Solutions** is the so-called [***Lightning Network***](https://lightning.network/){:target="_blank"}, developed in 2015 by Joseph Poon and Thaddeus Dryja.  
It works via [**bidirectional channels**](https://bitcoinmagazine.com/technical/understanding-the-lightning-network-part-building-a-bidirectional-payment-channel-1464710791){:target="_blank"} between nodes, and needs base transactions for opening, closing, rebalancing and routing. But once set up it can handle large volumes of transactions without the need for regular main net connection.  
Those protocols are meant to extend Bitcoin's functionality up to a point, while maintaining the base layer secure and decentralized ([**LN 2.0**](https://blog.theabacus.io/lightning-network-2-0-b878b9bb356e){:target="_blank"}).  
-- As such it has the potential for over [**1 million**](https://medium.com/@mnry.io/what-is-the-lightning-network-and-how-does-it-work-a9015096cc1c){:target="_blank"} TPS, just the right number, while keeping the fees low. Still it should be mentioned that this is not necessarily the ultimate fix and still hase some challenges.  
-- Also worth noting is that it is not currently feasible for every person on the planet to have a fully custodial lightning wallet with its own node. With current transaction throughput we could see each year opening up to 100 000 new channels, relatively slow for global population. Instead, a more realistic approach is to have many distributed custodians.  
-- In fact every bank could become custodian and a lightning node (distributed and dispersed hub-and-spoke network architecture). On top of that maybe only few percent of the global population will have self custody, with either completely or partially trustless implementation.  

-- So in the next 20+ years if few billion people, would start using it we could expect around 50 000 nodes with average 100 K users. Of course there would be a small number of ones with million users and also many small ones with few hundreds users - Normal Distribution of banking, as currently there are around 25 000 [banks globally](https://www.linkedin.com/pulse/how-many-banks-globally-david-gyori){:target="_blank"}. ([Mega banks vs Community banks](https://www.extractable.com/insights/by-the-numbers-mega-banks-vs-community-banks/){:target="_blank"}.)  
-- Also it is expected from big corporations to have their own nodes and channels with vendors for payment, while small companies would use custodian banks. Just like large enterprises have their own accounting sector, while smaller ones hire external service from accounting bureaus. 

-- For better understanding a simple analogy is when you open a beer tap with bartender and at the end of night it gets settled with finality. In practice request for payment is send from receiver as Lightning Invoice, that can be with defined amount, or empty and left for sender to enter it.   
-- Another issue that Lighting improves upon is **Privacy** as transactions are not publicly visible on the chain.  
LN also adds support for miliSats a sub Sat (1/1000), with higher decimal precision for microtransactions and streaming payments (Sats [symbol](https://bitcoinmagazine.com/culture/my-suggestion-for-the-bitcoin-sats-symbol){:target="_blank"}). 

There are several [**implementations**](https://medium.com/@fulgur.ventures/an-overview-of-lightning-network-implementations-d670255a6cfa){:target="_blank"} of the protocol, notably:  
-***C-lightning*** developed by Blockstream in C language  
-***Eclair***, french for Lightning, a Scala implementation by ACINQ  
-***LND*** (Lightning Network Daemon) node by Lightning Labs in Go  

Technical difficulties and solutions:  
-finding viable paths -> Pickhardt routing  
-privacy leakages -> PTLCs (Point Time Locked Contracts), trampoline routing  
-force-closed channel -> solves itself with time  

[**Research**](https://river.com/learn/files/river-lightning-report-2023.pdf){:target="_blank"} by River (2023), [Fidelity Report](https://www.fidelitydigitalassets.com/sites/g/files/djuvja3256/files/acquiadam/FDA_TheLightningNetwork_ExpandingBitcoinUseCases_1187503.1.0_V5.pdf){:target="_blank"} as well as Analysis [Engine](https://1ml.com/){:target="_blank"} 

Bitcoin Lightning wallets - [**Comparison**](https://darthcoin.substack.com/p/lightning-wallets-comparison){:target="_blank"} (by *darthcoin* @substack):  
![wallets](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-wallets-all.jpg)

Self-Custody LN wallets - [**Test**](https://anitaposch.com/lightning-wallet-test-2024){:target="_blank"} (by *AnitaPosch* - tested in Africa):  
***Phoenix, Mutiny, Blixt, Green, Zeus,** Wallet of Satoshi*(custodial), with conclusion:  
*Phoenix topped the rankings for its overall performance and reliability, followed by Mutiny for its user-friendliness.*

Next is a table with selected ones that are fully mobile wallets.  

| Wallet | Github | Team | Vid | Tags |
| -----  | ------ | ---- | --- | ---- |
| 1.**Custodial** | ------ | ---------- | --- | --------------- |
| [**Wallet of Satoshi**](https://www.walletofsatoshi.com/){:target="_blank"} | Not OS | Daniel Alexiuc - Australia | [YT](https://www.youtube.com/watch?v=sXBwRO7ML7w){:target="_blank"} | easy, no fees |
| [**Strike**](https://strike.me/){:target="_blank"} | Not OS | Jack Mallers - US | [YT](https://www.youtube.com/watch?v=4-vJ7zZQ4wU){:target="_blank"} | - |
| [**Blink**](https://www.blink.sv/){:target="_blank"} | [Galoy](https://github.com/GaloyMoney/blinkbtc){:target="_blank"} | Nicolas Burtey - El.Sal. | [YT](https://www.youtube.com/watch?v=q3QwxCd1EZE) | [StableSats] |
| 2.**Non-Custodial** | *------* | *----------* | *---* | *---------------* |
| [**Phoenix**](https://phoenix.acinq.co/){:target="_blank"} | [Acinq](https://github.com/ACINQ){:target="_blank"} | Pierre-Marie - Paris, FR | [YT](https://www.youtube.com/watch?v=hmmehTnV3ys){:target="_blank"}| [trust-minimized] |
| [**Breez**](https://breez.technology/mobile/){:target="_blank"} | [BreezMobile](https://github.com/breez/breezmobile){:target="_blank"}| Roy Sheinfeld - Israel | [YT](https://www.youtube.com/watch?v=lcBsn8e-oQ4&t=407s){:target="_blank"} | - |
| [**Blixt**](https://blixtwallet.github.io/){:target="_blank"} | [blixt-wallet](https://github.com/hsjoberg/blixt-wallet){:target="_blank"} | Hampus Sjöberg - Sweden | [YT](https://www.youtube.com/watch?v=5JyOAeaCN0o){:target="_blank"} | - |
| [**Zeus**](https://zeusln.com/){:target="_blank"} | [ZeusLN](https://github.com/ZeusLN/zeus){:target="_blank"} | Evan Kaloudis - NY, US | [YT](https://www.youtube.com/watch?v=hmmehTnV3ys&t=1106s){:target="_blank"} | - |
| 3.**With On-Chain** | *------* | *----------* | *---* | *---------------* |
| [**Electrum**](https://electrum.org/){:target="_blank"} | [spesmilo](https://github.com/spesmilo/electrum){:target="_blank"} | Thomas Voegtlin - Berlin, DE | [YT](https://www.youtube.com/watch?v=pyylkpR4DDk){:target="_blank"} | [external node] |
| [**BlueWallet**](https://bluewallet.io/){:target="_blank"} | [BlueWallet](https://github.com/BlueWallet/BlueWallet){:target="_blank"} | Nuno Coelho - Barcelona, ES | [YT](https://www.youtube.com/watch?v=iVPNk2ZZ63w){:target="_blank"} | [external node] |
| [**Green**](https://github.com/Blockstream/green_android){:target="_blank"} | [Blockstream](https://github.com/Blockstream/green_android){:target="_blank"} | Adam Back - US | [YT](https://www.youtube.com/watch?v=DesN85bWmGA){:target="_blank"} | [external node] |
| [**Wasabi**](https://wasabiwallet.io/){:target="_blank"} | [WalletWasabi](https://github.com/WalletWasabi/WalletWasabi){:target="_blank"} | Max Hillebrand(DE) - Gibraltar | [YT](https://www.youtube.com/watch?v=ECQHAzSckK0){:target="_blank"} | [No more CoinJoins](https://thedefiant.io/news/regulation/wasabi-wallet-to-eliminate-coinjoin-amid-u-s-regulatory-fears){:target="_blank"} |

Network [**Topology**](https://appliednetsci.springeropen.com/articles/10.1007/s41109-023-00602-2){:target="_blank"} and [graph](https://lnrouter.app/graph){:target="_blank"} (distribution of nodes):  
![graph](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/lightning-graph.jpg)

-- Should the need arise, the process for onboarding users can be increased even more with [**Channel Factories**](https://bitcoinops.org/en/topics/channel-factories/){:target="_blank"} for [scalability](https://bitcoin.stackexchange.com/questions/67158/what-are-channel-factories-and-how-do-they-work){:target="_blank"}. Others optins in development include: [sidecar channels](https://lightning.engineering/posts/2021-05-26-sidecar-channels/){:target="_blank"}, [statechains](https://medium.com/@RubenSomsen/statechains-non-custodial-off-chain-bitcoin-transfer-1ae4845a4a39){:target="_blank"}, [inherited IDs](https://github.com/JohnLaw2/btc-iids/blob/main/iids14.pdf){:target="_blank"} and also [OP_CTV](https://medium.com/@diego.astoin/navigating-bitcoins-future-comparing-op-cat-op-ctv-and-beyond-1314850a34f1){:target="_blank"} (Check Template Verify) proposition for [**Covenants**](https://bitbox.swiss/blog/what-are-bitcoin-covenants/){:target="_blank"} ([scale beyond](https://www.rhinobitcoin.com/blog/bitcoin-covenants-can-we-scale-beyond-100m-users){:target="_blank"}), as well as [Ark protocol](https://bitcoinmagazine.com/technical/how-ark-plans-to-scale-private-bitcoin-payments){:target="_blank"}.  
Then another possibility are federated nodes like [FediMint](https://fedimint.org/){:target="_blank"} that are using federation model for governance. Also there is [BitSNARK & Grail](https://sovryn.com/bitcoinos){:target="_blank"} (Bitcoin [Rollups](https://decrypt.co/228630/bitcoin-rollups-bitcoinos-whitepaper-10x-transaction-speed){:target="_blank"}), and [Stacks](https://www.stacks.co/){:target="_blank"} as well.  
-- In the meantime there is an interesting use case for stableSats (StableCoins alternative), like dollars equivalent on top of Bitcoin network, e.g. for remittances. Particularly useful in the global south where many local currencies are quite unstable with very high inflation. Since [*Mutiny*](https://blog.mutinywallet.com/mutiny-wallet-is-shutting-down/){:target="_blank"} wallet was canceled another one with similar feature is [10101](https://10101.finance/){:target="_blank"} (ten-ten-one) finance (UPDATE: it also is [shutting down](https://10101.finance/blog){:target="_blank"}). Also there is [Aqua](https://aquawallet.io/){:target="_blank"} wallet with [Liquid Network](https://liquid.net/){:target="_blank"} (federated side-chain).



YT talks to listen:  
-[Bitcoin's Lightning Network](https://www.youtube.com/watch?v=rrr_zPmEiME){:target="_blank"} (*Simply Explained*)  
-[What is the Lightning Network?](https://www.youtube.com/watch?v=pBh4DcM-0pg){:target="_blank"} (*99Bitcoins*)  
-[What is it? why should I care?](https://www.youtube.com/watch?v=AYAreuNzx58&t=39s){:target="_blank"} & [Non-Technical Explained](https://www.youtube.com/watch?v=XCSfoiD8wUA){:target="_blank"} (*Andreas Antonopoulos* - [*aantonop*](https://aantonop.com/){:target="_blank"})  
-[Lightning Made Easy](https://www.youtube.com/watch?v=nusOl6wb1a4){:target="_blank"} & [LN with Phoenix](https://www.youtube.com/watch?v=9j_slmZ7Eyo) (*Bitcoin University*)  
-[Scaling Bitcoin with Giacomo, John & Matt](https://www.youtube.com/watch?v=Iz81W-_X5gw){:target="_blank"} (*WBD - What Bitcoin Did*)  

More scientific papers:  
-[nakamotoinstitute/funding-of-micropayment-channel](https://nakamotoinstitute.org/static/docs/scalable-funding-of-bitcoin-micropayment-channel-networks.pdf){:target="_blank"}  
-[lightning-pool-whitepaper](https://lightning.engineering/lightning-pool-whitepaper.pdf){:target="_blank"}  
-[MA_EEMCS](https://essay.utwente.nl/80780/1/Wijburg_MA_EEMCS.pdf){:target="_blank"}  

Dashboard info:  
-[mempool.space/lightning](https://mempool.space/lightning){:target="_blank"}  
-[clarkmoody.com/dashboard](https://bitcoin.clarkmoody.com/dashboard/){:target="_blank"}  
-[bitbo.io](https://bitbo.io/target="_blank")  

Previous Bit posts:  
B1. [**(r)Evolution of Money**](https://infopedia.io/revolution-of-money/)  
B2. [**Bitcoin future and macro outlook**](https://infopedia.io/bitcoin-future-macro-outlook/)  

PS  
If you have business or provide services consider to start accepting Bitcoin (circular economy), sticker for print:   
(one personal example with prices also denominated in BTC - [codis.tech/efcorebulk](https://codis.tech/efcorebulk){:target="_blank"})  
![bit-acc](https://raw.githubusercontent.com/borisdj/borisdj.github.io/main/assets/images/lightning-network/bit-acc.png)  
Donation for support: [BTC-LN](https://borisdj.net/donation/donate-btc.html){:target="_blank"}  
(also to support the developers: [Donation Portal](https://bitcoindevlist.com/){:target="_blank"} or ili [OpenSats](https://opensats.org/){:target="_blank"})

<center>QR Link</center>
![QR Link](https://quickchart.io/qr?text=https://infopedia.io/lightning-network/)

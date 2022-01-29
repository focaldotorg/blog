---
layout: post
title: "The Equitable Token Merger"
image: /assets/img/olongtea.png
permalink: the-equitable-token-merger
description: "Protocols eating protocols"
date: "28/01/2022"
---
Decentralised governance is a sensitive and unexplored topic of technology, yet many of the current instances slack at the core upon closer examination. This blog acts as a medium for thought on the many instances and experiments of governance in the field of web3.

_It is recommended readers compliment each edition with a soothing hot cup of tea of their preference, as the road ahead is dark, uneven, and cold._

![image](/assets/img/olongtea.png)

Acquisitions are nothing new, still in of themselves require nurturing with - time, capital, and compliance. Dealt in the private domain, shareholders fit the demographic of investor or employee and authority is hierarchical. These actors shape the nature of the deal relative to the counterparty, transferring all rights for monetary gain. Where there were companies, there are now protocols.

Some “fat” facilitate a data layer, others more “thin” populate an application layer within, as described in the [fat protocol thesis](https://www.usv.com/writing/2016/08/fat-protocols/). The stakeholders in these systems differ, fat protocols rely on nodes to process and constitute the validity of network actions derived from the underlying consensus algorithm. Thin protocols tend to define contributors via a native “token”, often streamlined as incentives to bootstrap participation and contribution, **allocating governing power to users and actors alike**. These share the topology of a [flat organisation](https://en.wikipedia.org/wiki/Flat_organization), where no mere actor is more significant than the other.

It is common for thin protocols to use a weighted voting model, which has the potential for such structure but only if distributed equitably, if not hierarchies can form. Consensus is sufficiently achieved through fulfilling quorum, which more than often can be a low value to strafe from poor voter turnouts. Fat protocol consensus mechanisms differ in each instance, the native “coin” commonly upholds no  authority but the resource committed to secure the network does. An example being Bitcoin’s Proof of Work (PoW), where computational power secures and directs the longevity of the network. Other models like Proof of Stake (PoS) function through a consortium model, where each peer stakes a constant denomination of the native asset. Consensus in each instance is enforced through [Byzantine fault tolerance](https://en.wikipedia.org/wiki/Byzantine_fault) (BFT), and in the presence of foul play, adversaries are exonerated at cost of their commitment.

Legacy organisations regardless of their top-down formation, exemplify **some** autonomy in the early stages but eventually diminish upon scaling to corporates. Evaluations either public or private, are derived from an entity's revenue streams, employee count, share float, and presence. The economics and voting dynamics of company shares, rarely refract from the dividend and weighted model, retaining benchmarks of this asset class consistent. Aspects of which can be abstracted to decentralised protocols, but for the most part are inadequate quantifications of relative value. Native assets across thin and fat protocols, drastically diverge in their economics, utility, and authority.

Publicly traded assets throughout their lifetimes can inhibit value accrual from speculation which can be fuelled by economical theory, but more often roots from social sentiments. Arguing that the free market is the basis for determining asset value, leaves the way open for market manipulation.

<blockquote class="twitter-tweet"><p lang="en" dir="ltr">if markets reward coercion one should avoid thinking about price as a proxy for success</p> <a href="https://twitter.com/ssaintleger/status/1472207230971924490?ref_src=twsrc%5Etfw"><svg class="svg-icon grey"><use xlink:href="/assets/minima-social-icons.svg#twitter"></use></svg> - sacha saint-leger🎗 (@ssaintleger)</a></blockquote>

That said, how can one approach deriving relative value across these cooperatives of open collaboration, we know that governance is a necessity at the core of any form of coordination. While monetised votes have always been controversial to the architecture of a governing body, it is nothing new in the world of capitalism. In 1946, a revelation to [governance and game theory was formalised](https://en.wikipedia.org/wiki/Penrose_square_root_law) by Lionel Penrose. This was then applied upon by John F. Banzhaf the third, to create a methodology distinguishing the probability of a singular actor `i` in a set of `n` voters that could skew the outcome of a ballot, known as the [Banzhaf power index](https://en.wikipedia.org/wiki/Banzhaf_power_index).

On the 8th of November 2021, discussions were unveiled across the public discourses of Gnosis and xDAI [about a potential merger](https://forum.gnosis.io/t/gip-16-gnosis-chain-xdai-gnosis-merge/1904) authored by the internal management of each organisation. The basis point for this benchmark relied on 14 day time-weighted average price queries to central markets to compute a pre-defined exchange rate, [which was criticised](https://forum.poa.network/t/xdai-gnosis-merger/8357/61) because of GNO's recent all time highs in the market versus STAKE's lows. It was retracted for a model [with a multiplier](https://forum.gnosis.io/t/gip-16-gnosis-chain-xdai-gnosis-merge/1904/73) which had more acceptance. A month later, the ballots were live and coordinated through the vote signalling solution [Snapshot](https://snapshot.org), **enforced with no quorum**.

As we walk into a new era of commoditisation and public goods, open initiatives are not refrained by the shackles of top-down droit. Therefore, all acts of founder interaction should digress from conflicts of interest.

_For the sake of simplicity, this analysis only constitutes the top 100 EOAs (including multisigs) of a circulating supply and the remainder being represented as a singular coalition representing all minor actors for each distribution. This data concerns the timeline precedent to 16-12-2021, and was sourced from Etherscan, Blockscout, and using a custom BigQuery script to derive STAKE holdings converted to GNO. View the raw data, calculations, and charts [here](https://docs.google.com/spreadsheets/d/1CJGrX9-ADQgaeRLxRGoDQw71XoeJ3ybfGj5NqE64sAI/edit?usp=sharing)._

## xDAI

One of the first tangible scaling solutions presented to Ethereum, one that did not wish to compete but instead foster the components of its parent network to help negate transactional costs. Achieved through specifying the base currency with the stablecoin DAI, through bridging it from Ethereum. Originally conceptualised as a Proof of Authority (POA) test network for developers, xDAI blossomed into a landscape for creatives and experiments. Incubating innovations such as the real-time zkSNARK strategy game [Dark forest](https://zkga.me/), Omnibridge, and the xDAI bridge which provided cross-chain solutions with swift finality. Like any iterations today, [are facilitated by multi-signature wallets](https://docs.tokenbridge.net/xdai-bridge/xdai-bridge-contracts-management).

The project eventually pivoted to a Delegated Proof of Stake (DPoS) consensus algorithm through issuance and application of the STAKE token. The core utility being its affordance for involvement in consensus but also was preached as a governance token. Although when [a multisig wallet manages the protocols treasury](https://etherscan.io/address/0x5e78c09984bd6608f8e913f0924062c043ed6ad7), it exerts doubts about the governance capacity of the token itself. While Snapshot is a useful tool for mitigating financial costs to partake in governance, it still is a system that depends on the assumption of trust between voters and executors to follow through on the underlying decisions polled. It is an ongoing issue with the widespread adoption of this tooling, let alone the theatre that is usually tallied with it.

It is becoming the norm to hold all ballots through this method begging critical inquiry. Context is important, states of criticality or contentiousness should be balloted on-chain. Furthermore, one should ask, what if the topic is contradictory to such executors - there is no backstop to prevent disobedience nor does a Snapshot poll verify prolonged commitments to any ballot, as it is merely a photograph of balances at a select block height. Hypothetically, if orchestrated subtly, an adversary with insider knowledge could purchase voting power prior to a proposal and then liquidate upon voting, reducing price exposure.

<figure>
  <img
  src="/assets/img/stake-top-100-holders.svg"
  alt="top-100-stake-holders" />
  <center>
   <figcaption>
     <i>Top 100 addresses holding STAKE across xDAI and Ethereum</i>
    </figcaption>
  </center>
</figure>

While STAKE has pockets of concentration, it is impressive in such a loose analysis to uncover that when the minor actors are aggregated, they act as the second-largest body. It is apparent that this asset's demographic is vast, as precedent to the recent buyout it was diversified through a merger with POA network. Consensus here is defined at 51% amongst all participants, as it would be in BFT. There are over 19 different elected cohorts facilitating the role of validators on the network, which one could argue is an improvement in comparison to some larger-scale networks with fewer nodes. 

**Address**|**STAKE**|**Banzhaf Index**
:-----:|:-----:
0x5e...6ad7|1372626|0.2444441863631056
REMAINING|1165637|0.1425486309512017
0xe9...241a|378916|0.11162407310432244
0x48...170d|193980|0.04764046071842599
0x96...4b59|191899|0.04710927926530592
0xb0...84af|138356|0.033634227664410724
0xd1...6d2c|131594|0.0319518370363876
0xa9...22ba|121977|0.029569718758782004
0x26...c81d|74997|0.018069970555026467
0x14...e68a|50387|0.012118857528735977
0x24...55b9|47314|0.011377663546395638
0x2c...7e55|46229|0.011116060497923111
0x86...40f9|43978|0.0105734750362733
0x64...e879|42382|0.010188891027342429
0x00...05fa|40000|0.009615082184289463
0x1c...a0e2|39346|0.009457573205846137
0x32...c5c6|37464|0.009004395504897542
0xe1...bd6e|32723|0.007863290142249136
0x0d...92fe|31323|0.007526454959667192
0x9f...aec4|30098|0.0072317690201023094
0x28...5ed1|25697|0.006173384591246561
0x18...bc1e|24865|0.005973351324965386
0xef...f8db|24466|0.005877427384666152
0x5d...413a|23784|0.005713475175518873
0xbc...5ca1|21269|0.005108954441632169
0x3e...03ba|20996|0.005043341972182873
0xbe...950a|20100|0.004828008198809365
0x16...1d0d|18568|0.004459858915724145
0x34...12f7|18009|0.004325537540373836
0x0a...c6fb|17258|0.004145088619893044
0x45...0162|17256|0.004144608075286944
0x67...521b|16865|0.0040506627799887255
0xad...dce9|15487|0.0037195896903293797
0x9c...91b1|14454|0.0034714223575922462
0x64...3ed3|14157|0.0034000738402902336
0x32...ee6b|13127|0.003152644717154841
0xf9...080a|12758|0.0030640057118445055
0x44...8cf9|11711|0.002812509844398831
0x70...41c7|11137|0.002674636433708613
0x34...6ece|10461|0.002512267062842477
0xe9...1cb0|10292|0.0024716753985762185
0x02...246e|10201|0.002449818457696532
0x4f...98c1|10018|0.0024058646177008
0x19...ecf0|10006|0.0024029824092218492
0x65...9d6b|10001|0.0024017814894025163
0xb0...effc|10000|0.0024015413054654733
0xe8...d8a6|10000|0.0024015413054654733
0xee...9131|10000|0.0024015413054654733
0xf8...b52a|9981|0.0023969778123590748
0x4b...4c9c|9975|0.0023955367099422966
0x7c...d7d6|9874|0.0023712782006223318
0xb5...d125|9586|0.0023021059128831996
0x90...986f|9208|0.0022113183605104044
0xfe...1ffb|9000|0.002161361693591051
0xf6...2da7|8878|0.002132060349511339
0xdc...ed97|8704|0.002090270111946481
0xe1...0f53|8527|0.0020477595947344463
0xbb...6dc4|8517|0.002045357877772434
0x46...e642|8454|0.0020302270783846246
0xc3...3443|8275|0.00198723655736115
0x05...ba39|8117|0.0019492898141427134
0xe3...6cac|8003|0.0019219106311174083
0x25...5ec3|7942|0.001907260404790542
0x83...d483|7705|0.0018503409218864973
0x0b...6601|7685|0.0018455376078661094
0x26...916b|7683|0.0018450572766153482
0x45...be99|7631|0.00183256867371887
0xf3...090d|7604|0.001826084214114598
0x17...dcdf|7533|0.0018090325106134763
0x89...c181|7149|0.0017168097930337818
0x14...23d9|6834|0.0016411590509800296
0x91...678b|6792|0.001631072331791892
0x16...6476|6629|0.001591926355801861
0x0c...27e7|6625|0.0015909657203497336
0xf0...e88b|6437|0.0015458159600184956
0xa2...5169|6354|0.0015258828862300077
0x6d...39e0|6274|0.0015066703220361216
0x22...b9ff|6244|0.0014994656197441839
0x44...e480|6073|0.00145839891190472
0xb8...4901|6022|0.0014461509773511922
0x79...e902|5997|0.0014401470929868562
0xdb...4298|5954|0.001429820419711905
0x4b...f762|5690|0.0013664196619794862
0x4d...3591|5595|0.001343605082989271
0xb8...1850|5567|0.0013368807946730257
0x7b...f7a1|5394|0.001295334384800477
0x70...3310|5325|0.0012787638919104724
0x4e...b6ed|5297|0.001272039640408809
0x01...09ef|5284|0.0012689176677607784
0xe4...2431|5261|0.0012633941796460321
0x43...5e5f|5001|0.0012009549192554467
0xed...66c1|5000|0.0012007147688475905
0x3a...e43c|4971|0.00119375040896099
0x15...4924|4881|0.0011721369019841183
0xbd...85a0|4653|0.0011173828410420876
0xfb...c4bc|4466|0.001072475067013981
0xb5...2bbf|4302|0.001033090824181557
0xde...4821|4111|0.00098722272029753
0xa9...1959|4000|0.0009605664496889018

<figure>
<center>
  <figcaption>Figure 2: STAKE power distribution </figcaption>
</center>
</figure>

Computing the power distributions shows us that the largest singular actor is actually the treasury (as expected), as it is internally managed through a multisig, therefore, isn't a piece of infrastructure. The disparity between the top 3 actors and the remainder seems equitable at first glance but is diminished by the restraints of computing the Banzhaf power index for large `n` player finite games, and the attempt to negate this by clustering all minor actors into a singular coalition.

For such a critical proposal that dictated the future of the network, it seems the turnout wasn't quite what is deemed as consensus in distributed systems. According to the [xDAI proposal](https://snapshot.org/#/xdaistake.eth/proposal/0x646cd97b769b4f1b7d7223b46f5e6ded097ae2ee3e0f1433a7b597e021a4d6d4); a total of 1,210,318 STAKE out of the circulating amount of 4,991,236 STAKE was only cast to the ballot. A ratio of 1:2.1 to the quorum, which is quite the divergence.

<figure>
  <img
  src="/assets/img/stake-gno-ballot.svg"
  alt="stake-gno-ballot" />
  <center>
   <figcaption>
     <i>Figure 3: Voter demographic of the STAKE proposal</i>
    </figcaption>
  </center>
</figure>

On light inspection three addresses stand out in this demographic, the major actor [0xe96...0d12](https://etherscan.io/address/0xe965484BA4250c446779D4703f1598DC2EA00d12) was delegated weights from the multisig address [0xbc...26bb](https://etherscan.io/address/0xbc79855178842fdba0c353494895deef509e26bb#tokentxns) that has direct association to [the Gnosis partnership with xDAI](https://forum.poa.network/t/xdai-gnosis-merger/8357/5) and provided the majority of liquidity to GNO/STAKE Uniswap V3 pool. Then [0xFe...b7F4](https://etherscan.io/address/0xFe13988736d95D052C2E45e5b4E1Ef2e2750b7F4) that [purchased approximately $425,000](https://etherscan.io/tx/0xec0bfea340535c5e3261a7c2f6c5e220ebb18a4a9ba46eb92eccc21cf3e8c7ba) of STAKE and [0x454...be99](https://etherscan.io/address/0x454ce089a879f7a0d0416eddc770a47a1f47be99) that [bought $100,000](https://etherscan.io/tx/0xd1ab6577a3df664df8e6b7a16d266427b896f1c257c16ea38286d4e6f6538a53) a day before the ballot went live.

Not that any of these actions are unethical, this is just the nature of monetised voting but it does show us the sheer influence the counterparty had. From these three addresses alone, they held approximately 30% of all voting weight in the ballot, and this is without a thorough analysis of all actors. The fact that this proposal did not adhere to the standard of a fat protocol is a matter of concern.

## Gnosis

The owls are not what they seem, some say. Gnosis originally a prediction market on Ethereum, incepted amidst the gold rush of 2017 and [catalysed from a "poorly designed" Dutch auction](https://www.coindesk.com/markets/2017/04/24/ico-insanity-300-million-gnosis-valuation-sparks-market-reaction/) where 95% of the supply was retained by the internal players. From day one, with 250,000 ETH raised it was a behemoth. Although that amount is measly today compared to the many wallets that Gnosis operates from [serial investing](https://www.scribd.com/document/474588193/Gnosis-Pitch-Deck-pdf) and [trading](https://twitter.com/koeppelmann/status/1300761124305072130) - with of course, the money raised that was supposed to build out a protocol of value. While the premise of prediction markets was endorsed as revolutionary back in the dissonance of 2017, we know today that this was a fallow statement - from an inability to capture traction, [the concept being subject to regulatory scrutiny](https://www.natlawreview.com/article/who-would-have-predicted-it-polymarket-settles-operating-unregistered-swap-execution) and the delusion of [futarchy](https://en.wikipedia.org/wiki/Futarchy) having extensive benefits to a governing body (more on that later).

Gnosis Ltd, knew this all too well as overcast foreshadowed the markets and eventually were [criticised](https://www.theblockcrypto.com/post/76453/arca-gnosis-defi-project-call). They quickly pivoted and found their niche in bringing open-source tooling to Ethereum, notably of which was multi-signature wallets. An essential form of tooling to mitigate risk in fund management. The accessibility granted through developing and publicising such tooling has had immense benefits for individuals and open organisations. The question still remained of their token utility, and [still seemed to be an ongoing narrative](https://forum.gnosis.io/t/gno-utility-and-value-proposition/2344) up until the acquisition.

While we could talk all day about the many ventures Gnosis ignited, whether successful or failures, for internal financial gain or for public goods. It is worthy to note their resilience. Furthermore, while the organisational structure is less like a protocol and more like a [corporation](https://twitter.com/jdorman81/status/1324732721889828865), let's investigate how their journey towards decentralisation is going.

<figure>
  <img
  src="/assets/img/gno-top-100-holders-unprofiled.svg"
  alt="top-100-gno-holders-unprofiled" />
  <center>
   <figcaption>
     <i>Figure 4: Top 100 addresses holding GNO on Ethereum</i>
    </figcaption>
  </center>
</figure>

We see a relative similar topology to xDAI's stakeholders, the contrast being the remaining minor coalition is only the 5th largest and versus contracts (which is outside the scope of this analysis), are approximately 30% more concentrated. Where quorum is defined at 51%, as if we were to use [gnosis's own value at 4%](https://snapshot.org/#/gnosis.eth/proposal/QmdjWuBnBnPUafW9jBNNsJJvaeQAVExGcFZ7zB38VtNuu4) - it would be infeasible to compute the index due to the probabilistic constraints.

**Address**|**GNO**|**Banzhaf Index**
:-----:|:-----:|:-----:
0x2e...6a13|282543|0.31079299006291866
0x9d...53d5|133364|0.07898748651781151
0xaf...c0d6|75000|0.05124487198407653
0xfc...a2e8|71618|0.04897624251003832
REMAINING|66750|0.04568859217933548
0xa4...46c1|50251|0.03448033366956244
0x1d...a341|50001|0.034309766469972795
0xad...76e3|41168|0.02827310059328169
0x62...3112|38438|0.026404028670435904
0x97...a73b|38230|0.02626156728736583
0xae...d7a9|34951|0.024014807533713222
0xfe...b7f4|31224|0.021459052732673515
0x2d...5cdd|26999|0.018559628052894864
0xb1...c269|25000|0.01718711058280377
0x39...ebdf|23928|0.01645090864231301
0xe9...40e8|19562|0.013451479099828452
0x9e...ca61|16627|0.011434344111027056
0xbc...26bb|16591|0.011409598867211022
0xde...6870|13779|0.00947649192556307
0xfb...bb98|13492|0.009279170462733315
0x94...a3a3|13018|0.008953271939631054
0x95...1dc3|11857|0.008154983270337854
0x57...593e|11111|0.007642012773520306
0xf5...2764|10000|0.006878017735743157
0xa8...0bb6|9320|0.006410384125780234
0x40...3ddd|7756|0.005334770954634757
0x55...f224|6955|0.004783870788886505
0x7d...41b4|6103|0.004197877469347734
0x28...1d60|6016|0.004138039215161724
0x41...4c6b|5946|0.004089893377794901
0x53...efc4|5942|0.004087142184002658
0x8f...3b0c|5797|0.0039874111866138725
0x49...9ec6|5680|0.003906938277956872
0x29...0858|5000|0.003439227290678738
0xe3...0e18|4691|0.003226691185925732
0x0c...56ec|4665|0.003208807816477484
0x81...f1e1|4392|0.003021031785892139
0x67...1c87|4379|0.0030120900411596306
0x00...0497|4207|0.0028937836404990076
0xf0...8461|3922|0.002697751741029259
0x75...8608|3557|0.0024466917361390915
0xec...63fb|3537|0.0024329349743849983
0x44...2a3f|3502|0.0024088606294971077
0x46...26e9|3479|0.002393040337584361
0x64...e5f1|3414|0.0023483307825139083
0xcd...944e|3408|0.0023442037441190728
0x55...da65|3330|0.0022905522064550965
0x7d...9530|3116|0.0021433540413478285
0x42...c62f|3042|0.0020924536241649673
0xea...b9a4|3013|0.00207250614751555
0x1f...2aef|2922|0.002009912284721754
0x5d...6905|2896|0.001992028308371022
0x49...e462|2891|0.001988589081368263
0xfe...ab3e|2722|0.0018723430638347715
0xdd...3544|2455|0.0016886875694740904
0xce...250a|2446|0.001682496923875317
0x57...a4a2|2382|0.0016384745354854299
0x39...04f7|2104|0.0014472519046249308
0xf5...dcb3|2038|0.0014018536403934995
0x12...8034|1991|0.001369524554601292
0xa4...8aa9|1989|0.001368148848481798
0x22...cb32|1947|0.0013392590136376353
0x12...109c|1731|0.0011906825375149863
0x08...9ffb|1660|0.0011418448366306796
0xee...a1e5|1605|0.001104012794799654
0x90...de31|1598|0.001099197806437207
0x65...e6b2|1513|0.0010407300692846717
0xd0...549d|1508|0.0010372907894268864
0xb0...00ec|1424|0.0009795108686037708
0xe5...c948|1411|0.0009705687348340199
0x74...c129|1384|0.0009519966082164706
0x70...87dc|1369|0.0009416787585790292
0x7c...55cb|1321|0.0009086616326170941
0xe6...8ac1|1309|0.0009004073494621078
0xed...c15e|1228|0.0008446909213655568
0x5f...9bef|1219|0.0008385002053739057
0x18...b73a|1205|0.0008288702020404591
0xf7...08a2|1200|0.0008254309149366431
0xd4...9988|1147|0.0007889744653245416
0x1d...b9fe|1093|0.000751830146683271
0x8f...0ec3|1039|0.0007146858169883382
0x8a...fa6f|1026|0.0007057436619533626
0x00...78d8|1005|0.0006912986410144979
0x10...48b9|997|0.0006857957754888846
0xb8...f2c9|980|0.0006741021855144276
0x00...cff3|966|0.0006644721695030913
0x05...fb7d|964|0.0006630964528762203
0x24...8e66|957|0.0006582814445770462
0xea...ec99|953|0.0006555300111901419
0xe9...837b|866|0.0005956863223222633
0x1f...109b|864|0.0005943106050607677
0xf7...4d0c|836|0.0005750505621540512

<figure>
<center>
  <figcaption>Figure 5: GNO power distribution </figcaption>
</center>
</figure>

 With observation to the remaining minor coalitions across both power distributions, GNO's minors have approximately 80% less influence in the system compared to STAKE. This value may be saturated due to the discrepancy in computing large finite games, and grouping all minor actors to negate this. Furthermore, if we were to make the assumption that there is a commonality amongst a selection actors of the demographic; such as being a multisig and retaining a majority holding in GNO, a different picture emerges.

<figure>
  <img
  src="/assets/img/gno-top-100-holders-profiled.svg"
  alt="top-100-gno-holders-profiled" />
  <center>
   <figcaption>
     <i>Figure 6: Top 100 profiled addresses holding GNO on Ethereum</i>
    </figcaption>
  </center>
</figure>

**Address**|**GNO**|**Banzhaf Index**
:-----:|:-----:|:-----:
MULTISIGS W/ GNO|879464|1
REMAINING|66750|0
0xae...d7a9|34951|0
0xfe...b7f4|31224|0
0x2d...5cdd|26999|0
0x39...ebdf|23928|0
0xbc...26bb|16591|0
0xde...6870|13779|0
0xfb...bb98|13492|0
0x94...a3a3|13018|0
0xf5...2764|10000|0
0xa8...0bb6|9320|0
0x40...3ddd|7756|0
0x55...f224|6955|0
0x7d...41b4|6103|0
0x28...1d60|6016|0
0x41...4c6b|5946|0
0x53...efc4|5942|0
0x8f...3b0c|5797|0
0x49...9ec6|5680|0
0x29...0858|5000|0
0xe3...0e18|4691|0
0x0c...56ec|4665|0
0x81...f1e1|4392|0
0x67...1c87|4379|0
0x00...0497|4207|0
0xf0...8461|3922|0
0x75...8608|3557|0
0xec...63fb|3537|0
0x44...2a3f|3502|0
0x46...26e9|3479|0
0x64...e5f1|3414|0
0xcd...944e|3408|0
0x55...da65|3330|0
0x1f...2aef|2922|0
0x5d...6905|2896|0
0x49...e462|2891|0
0xfe...ab3e|2722|0
0xdd...3544|2455|0
0xce...250a|2446|0
0x57...a4a2|2382|0
0x39...04f7|2104|0
0xf5...dcb3|2038|0
0x12...8034|1991|0
0xa4...8aa9|1989|0
0x22...cb32|1947|0
0x12...109c|1731|0
0x08...9ffb|1660|0
0xee...a1e5|1605|0
0x65...e6b2|1513|0
0xd0...549d|1508|0
0xb0...00ec|1424|0
0x74...c129|1384|0
0x70...87dc|1369|0
0x7c...55cb|1321|0
0xed...c15e|1228|0
0x5f...9bef|1219|0
0xf7...08a2|1200|0
0xd4...9988|1147|0
0x1d...b9fe|1093|0
0x8f...0ec3|1039|0
0x8a...fa6f|1026|0
0x00...78d8|1005|0
0x10...48b9|997|0
0xb8...f2c9|980|0
0x00...cff3|966|0
0x05...fb7d|964|0
0x24...8e66|957|0
0xea...ec99|953|0
0xe9...837b|866|0
0x1f...109b|864|0
0xf7...4d0c|836|0

<figure>
<center>
  <figcaption>Figure 7: GNO profiled power distribution </figcaption>
</center>
</figure>

What we see above is this assumed profiled coalition holding all governing power, and every other actor being disenfranchised or more commonly defined as [dummy candidates](https://en.wikipedia.org/wiki/Dummy_candidate). It goes without mentioning, that this benchmark does not include [the unallocated supply that Gnosis Ltd still manages](https://etherscan.io/token/0x6810e776880c02933d47db1b9fc05908e5386b96?a=0xec83f750adfe0e52a8b0dba6eeb6be5ba0bee535) with no strategic plan how to distribute for an equitable governance landscape. Only recently, did they launch “GnosisDAO” which is in fact, yes you guessed right - [a multisig](https://etherscan.io/address/0x0da0c3e52c977ed3cbc641ff02dd271c3ed55afe#readProxyContract). Not only does this constitute the means that GNO is not a governance token at the time of writing but if it was, it would be anything but democratic, one could even argue a dictatorship.  

## Conclusion

Protocols architected poorly set a bad precedent and standards for the industry, they are paradoxical to the true means of distributed systems and attempt to cash in on the value provided from so. Individual sovereignty is not only comprimised but non-existant. Protocols should not be designed in the faith of prolific actors, they should be equitable and diverse, or else they are just reflections of the inequitable societal structures we all know too well.

**Decentralised autonomous organisations at scale are not multi-signature wallets, they are smart contracts directly governed by all stakeholders**. This opens the field to many possibilities and potential attack vectors, yet the benefits of doing so far extend that of a conglomerate. They are agile and open to all actors. Furthermore, open organisations should have robust policies to define consensus providing defence from external; or case in point, internal exploitation.

Huge thanks to David Leech, Professor of Economics at Warick University for his research in [deriving more effective computations of power indices](http://homepages.warwick.ac.uk/~ecrac/twerp644.pdf), Ruben R. Puentedura who formalised [the theory into a python script](http://www.hippasus.com/resources/socialsoftware/index.html) and Heinrich Hartmann [optimising the algorithm with vectorisation](https://gist.github.com/HeinrichHartmann/8ec2e2245f2a70441257). I hope to contribute to this field myself as this blog progresses, upon realising [the potential application of parallel programming](http://isim.asu.edu/polya_acc.pdf).

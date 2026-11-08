---
layout: post
author: "Samuel J. Gosling"
title: "The Mathematics of Loyalty"
permalink: the-mathematics-of-loyalty
image: /assets/img/posts/i/kula-ring-map.jpg
keywords: "insitutional governance, plutocracy, polycentrism, polycentric voting, polycentricity, kula ring, gift economies, power indices, game theory"
abstract: "Reciprocity, capital markets and governance"
description: "A brief history on weighted voting, capital markets, corperate goverance and a proposal for something new."
date: "06/10/2026"
---

## Kula ring

Since the dawn of mankind, human relationships have been established from reoccurring experiences. The measure of how frequent, how positive or how negative interactions are, shape what we call trust between parties of any relationship. Which arguably functions adequcately through reciprocity. 

![Map of the Kula ring](assets/img/posts/i/kula-ring-map.jpg "Map of the Kula ring")

Take the Kula ring[^1] of the Trobriand islands as example, a ceremonial exchange system where shell necklaces (Soulava) travel clockwise and shell armbands (Mwali) move counterclockwise through an archipelago of island communities in the Solomon sea. The objects themselves hold little utilitarian value; their worth lies entirely in the relationships they represent. A chief who receives a Soulava is expected to reciprocate with a recipient of a Mwali - not immediately, but eventually. The delay is crucial. It creates obligation, builds anticipation, and tests commitment over time. 

The system only functions because participants trust that gifts given today will be reciprocated months or years hence. What the Kula ring demonstrates is that loyalty and trust are not instantaneous but accumulated gradually overtime. A trading partner who has participated faithfully for decades carries far more social capital than one that hasn't. The system inherently recognises that time, weight and history matter and yet many would argue trust cannot be formally modelled.

## Modelling trust
If we are to theorise an abstraction of what embodies trust ($T$), we must first define loyalty ($L$) the foundation upon which trust is built. Loyalty can be represented by three variables: magnitude ($M$) the positive or negative social impact an interaction has on a recipient, interactions ($n$) the total number of trust-affecting events since acquaintance, and time ($t$) how far into the relationship an interaction occurred, expressed as a proportion of the total duration.

$$
L = \sum_{i=1}^{n} M_i \cdot t_i \tag{1}
$$

Trust ($T$) can then be defined as the measure of loyalty relative to the total impact of a relationship. Trust and loyalty are not interchangeable, they are separate but dependent means of navigating interactions.

$$
T = \frac{L}{M_{total}} \tag{2}
$$

Let's apply these formulas to a grounded physical context to see how we can model trust.

> A friend you have known for 2 months in which you have had 5 interactions with varying magnitudes of $M = \{+6, +6, -8, +5, +7\}$
> 
> $L = \sum_{i=1}^{n} M_i \cdot t_i$  
> $L = 6(0.2) + 6(0.4) + 8(0.6) + 5(0.8) + 7(1.0)$  
> $L = 19.4$  
> $T = L / M_{total} = 19.4 / 32 = 0.61$
> 
> You are repaid on time ($M_{n+1} = 20$) at month 3, all prior interactions are recalculated as proportions of the new total duration:
> 
> $L_{new} = \sum_{i=1}^{n+1} M_i \cdot t_i$  
> $L_{new} = 6(0.13) + 6(0.27) + 8(0.40) + 5(0.53) + 7(0.67) + 20(1.0)$  
> $L_{new} = 32.94$  
> $T_{new} = L_{new} / M_{total} = 32.94 / 52 = 0.63$

Showcasing the small but substantial increase in trust, given that over the course of the final month no interactions occured, if the loan was repaid sooner the positive effects on trust would clearly visible. This tells us that trust is a product of commitment, which must be maintained through sustained interactions yet decays with time. 

## Corporate governance

When shareholders vote on company decisions, they are exercising power over an entity built through years of collective effort, customer relationships, and operational history. Yet our current system treats all votes identical regardless of whether acquired yesterday or held for decades. A hedge fund that purchased shares last week has the same voting power per share as a pension fund that has held for twenty years - despite having radically different exposure profiles to their financial decisions. This is the mathematical flaw at the heart of plutocracy - it ignores time. 

The defects trickle down even to aspects such as remuneration. When the public market's interests are prioritised rarely is it reflective of the past but generally the future quarterly and annual earnings reports. A scenario that played out at General Electric (GE) back in 2010, where since 1987 their pension program was entirely funded by employees and contributed billions to their bottom line margin. CEO Jeffrey Immelt claimed it was a "drag" to the company's fiscal operations, a comment that followed ending the defined benefit plan for employees in 2012, instead replaced with 401k compensation. GE then continued to spend up to 40 billion dollars up until 2020 on stock buybacks in an attempt to increase their financials to be attractive to the general market, all while company executives received increased pay and stock. By 2018 pensions were underfunded by a factor of 22.3 billion dollars, **the largest deficit in history of the S&P 500**.  Whether you served for over three decades at the company is not relevant. Whether you have managed your life around these promised incentives is not relevant. Whether you were allocated shares and held is not relevant - only the short sighted preference of the public market is.

*Therefore, how could we factor for loyalty in a capital-weighted system?*

Prior attempts in this domain simply model time-weighting largely as a stepped function for enhanced voting rights[^2], [loyalty shares](https://fr.wikipedia.org/wiki/Une_action,_une_voix#France) treat individual transfers as isolated lots that also make the measurement of influence difficult. Furthermore often lacks progressive representation, default implementations quoting a 2 year timespan as tenure, with it carrying double voting influence. Which can disenfranchise common ownership, analysis on NYSE data found the average market share holding time only reaching 5.5 months as reported June 2020[^3].

Like human relationships, shareholders should be given a degree of authority from simply being present and allocating their stake towards a dedicated function, as they already do through idle inventory. Although it can troublesome to treat public markets and stakeholder constituencies as equals. The latter being when shares or votes are committed towards the organisation's function, the former for provisioning shares for an economic incentive. One of the major defects of plutocracy is the ambiguity of voting power due to the accessibility and continuous nature of market liquidity.

## History of voting theory

Many dismiss the roots of voting theory and its impact yet it's an important angle that helps understand the flaws of weighted voting and dynamics of collective decision-making when choreographed incorrectly. In 1946, [Lionel Penrose](https://en.wikipedia.org/wiki/Lionel_Penrose) proposed a new method for voting demoted as the square-root method, its inception marked a turning point; saturating concentrations in power but respecting broad representation. It wasn't until 1954 when Penrose's theory would be validated further, when the Noble prize winner [Lloyd Shapley](https://en.wikipedia.org/wiki/Lloyd_Shapley) and [Martin Shubik](https://en.wikipedia.org/wiki/Martin_Shubik) theorised a metric to quantify the influence of voting power through combinatorial and probabilistic methods. Known as the Shapley-Shubik index[^4] it changed how we can understanding voting power and influence in any governing system, its first real thought-provoking application was an analysis regarding the UN security council[^5], Shapley and Shubik showed how the US veto clause effectively disenfranchised all members states. 

In what is now clearly a pivotal point when it comes to game theory and politics, consumer advocate [John F. Banzhaf III](https://en.wikipedia.org/wiki/John_Banzhaf) was inspired by the work of Lloyd and co, upon realising the skew of power when it came to Nassau county board governance. 

![New York Times 1991 Nassau County Board Lawsuit](assets/img/posts/i/nyt-1991-nassau-county.jpg "New York Times 1991 Nassau County Board Lawsuit")

Instead of accusations, John used cold cut mathematics through devising the Banzhaf power index[^6] to prove the disparity in representation of member townships due to weighted vote scoring. This followed by perusing legal action against the board, which in 1991 was successful enacting remodeling of the county's governance to a more democratic and egalitarian one-member one-vote model. Additionally acting as amicus curiae for Iannucci v. Board of Supervisors (1967), where the power index was referenced further.

Fast forward to the 21st century and the voting theory rebloom, widely unacknowledged that the flowers of which take inspiration from Penrose's square root law. Yet more commonly acclaimed being derived from early mechanism design point-purchase systems and optimal voting rules[^7].  Quadratic Voting proposed by [Weyl](https://en.wikipedia.org/wiki/Glen_Weyl) and [Posner](https://en.wikipedia.org/wiki/Eric_Posner) in 2017, uses the square-root function to replicate a "quadratic" cost in multiple choice voting ballots. It's only flaw is the need for Sybil protection, as it ultimately fails from the exponential advantage from what is called a splitting attack[^8]. Much is the reason why it has failed to be integral to capital markets but did find suite with Taiwan's digital ministry. With pilots for state budgets by preferential vote[^9] further validating the benefits of the square root method.

## Polycentrism 

Looking back at Kula ring and comparing it to corporate governance, the ancient exchange system had multiple degrees of authority such as time and commitment (accumulated through reciprocity; gifts, trading, marital agreements etc), whereas shareholder governance only has capital to equate to power. In 1951 [Micheal Polanyi](https://en.wikipedia.org/wiki/Michael_Polanyi) theorised the concept of **polycentrism**; which is defined as a network consisting of multiple independent centers, operating through a series of mutual adjustments. 

Plutocracy's intent was always to be polycentric but largely fails due to the ills of capitalism that it never achieves a flat organisational structure instead conforming to a hierarchy. The Kula ring is inherently polycentric not only because of the multiple degrees a participant must enact to gain authority but because the system is governed by the dozen of archipelago chiefs, no single actor has complete control or can shift the dynamics of the system alone.

## Something new 

What if time itself was the balance to a composite weighting system, one that penalises short-termism and amplifies tenure. Exactly the basis behind a new voting model for capital markets we designed named [Polycentric Voting](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=7546438). Where time and commitment are introduced as axes in authority past capital contribution, a system that that factors for tenure. Here we formalise **effective time ($t_{\text{effective}}$)**; a stake-time integral, resulting in dynamics where the time weight is rebalanced on subsequent deposits and preserved on reductions. 

$$
t_{\text{effective}} = \frac{\sum a_i \cdot t_d}{\sum a_i} \tag{3}
$$

Lets define four strategies for analysis, Singleton, Splitting, Dynamic and Sequential - note that Splitting concerns operating 100 accounts or stakeholder identities - each with a final share amount of 10,000 and varied inventory schedules:

<picture>
  <source srcset="assets/img/posts/i/pv_strategy_breakdown_dark.svg" media="(prefers-color-scheme: dark)">
  <img src="assets/img/posts/i/pv_strategy_breakdown_light.svg" title="Strategy breakdown">
</picture>

Seeking to factor for tenure in the modelling of voting power, we propose a novel weighting mechanism; a composite weight composed of root and linear ruling that deviates with time to purely linear. Where the proportion of linear to root is expressed as the **power ratio ($\alpha$)**, where a higher value translates to saturating larger actors influence and provide broader representation of the sum parts to those of the smaller. 

Where $S$ represents stake and $W$ equals to the time-weight leads us to define **voting power ($V_P$)** of any stakeholder as:  

$$V_P = W(\alpha \cdot S + \sqrt{S}(1-\alpha)) \tag{4}$$

<picture>
  <source srcset="assets/img/posts/i/pv_strategies_dark.svg" media="(prefers-color-scheme: dark)">
  <img src="assets/img/posts/i/pv_strategies_light.svg" title="Strategy benchmark">
</picture>

When plotted we can see disparities between the strategies, first how Singleton and Splitting have almost equivalent voting power, ruling that splitting attacks are largely self-defeating with additional operational cost. While there is minor advantages in voting power under the Splitting strategy, it is temporary and fully dissipates at convergence. Sequential converging soon after as it only concerns deposits, Dynamic posing as suboptimal from greater dilution and thus duration to convergence due to rebalancing. 

Finally, under analysis using the Banzhaf power index, we discovered influence follows a dynamic order under this voting model in contrast to static order of traditional shareholder voting.

## Open organisations

Through the process of establishing a new answer to collaborative decision-making, the reality of its integration appeared stark given that traditional corporate governance treats shareholder distributions as confidential material. To the extent that to develop tooling to allow traditional organisations to experiment with what has been proposed here, would require collaboration with multiple service providers and the bureaucracy that comes with it.

Hence for now,  we developed infrastructure to enable this work on [Ethereum](https://ethereum.org), giving agency for anyone to bootstrap an organisation without any restrictions and with little overhead. We analysed the state of current governance frameworks and standards on the network to immediately observe boundaries. Albeit to provide a seamless integration path to new and existing organisations, we present [Governor Delta](https://github.com/focaldotorg/governor-delta) as a true successor to the Bravo implementation that many organisations operate under today.

Expect further commentary and publications.

[^1]: Malinowski, *Argonauts of the Western Pacific* (1922)
[^2]: Berger D.J., Solomon, S.D., Benjamin A., *Tenure Voting and the U.S. Public Company*, The Business Lawyer, Vol. 72, No. 2 (2017)
[^3]: Chatterjee S., Adinarayan T., *Buy, Sell, Repeat* (2020), Reuters Media
[^4]: Shapley & Shubik, *A Method for Evaluating the Distribution of Power in a Committee System* (1954)
[^5]: Shapley & Shubik, *The Application of Power Indexes to World Politics* (1954) 
[^6]: Banzhaf, *Weighted Voting Doesn't Work* (1965)
[^7]: Hylland & Zeckhauser, *The Efficient Allocation of Public Goods* (1979); Ledyard & Palfrey, *The Provision of Public Goods Under Alternative Electoral Institutions* (1994)
[^8]: Douceur J.R., *The Sybil Attack* (2002), Microsoft Research
[^9]: A. Tang, Sheau-Tyng Peng, *Quadratic Voting and Common Ownership Self-Assessed Tax (2019)*


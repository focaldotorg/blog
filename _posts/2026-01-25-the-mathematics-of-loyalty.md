---
layout: post
author: "Samuel J. Gosling"
title: "The Mathematics of Loyalty"
permalink: the-mathematics-of-loyalty
image: /assets/img/posts/i/kula-ring-map.jpg
keywords: "insitutional governance, plutocracy, polycentrism, polycentric voting, polycentricity, kula ring, gift economies, power indices, game theory"
description: "Reciprocity, capital markets and governance"
date: "25/01/2026"
---

## Kula ring

Humans since the dawn of early intelligence have operated or retaliated through relationships derived from reoccurring experiences. The measure of how frequent, and how positive or negative interactions are, shape what we call trust between parties of any relationship, which function constructively through reciprocity. 

![Map of the Kula ring](assets/img/posts/i/kula-ring-map.jpg "Map of the Kula ring")

Take the Kula ring[^1] of the Trobriand islands as example, a ceremonial exchange system where shell necklaces (Soulava) travel clockwise and shell armbands (Mwali) move counterclockwise through an archipelago of island communities in the Solomon sea. The objects themselves hold little utilitarian value; their worth lies entirely in the relationships they represent. A chief who receives a Soulava is expected to reciprocate with a recipient of a Mwali - not immediately, but eventually. The delay is crucial. It creates obligation, builds anticipation, and tests commitment over time. 

The system only functions because participants trust that gifts given today will be reciprocated months or years hence. What the Kula ring demonstrates is that loyalty and trust are not instantaneous - they are accumulated through repeated cycles, weighted by time. A trading partner who has participated faithfully for decades carries far more social capital than one that hasn't. The system inherently recognises that time, weight and history matter, and yet, many would argue "trust" cannot be quantified.

## Modelling trust

If we are to identify the core pillars of what constitutes trust ($T$), we must first define loyalty ($L$) the foundation upon which trust is built. Loyalty is determined by three variables: magnitude ($M$) the positive or negative social impact an interaction has on a recipient, interactions ($n$) the total number of trust-affecting events since acquaintance, and time ($t$) how far into the relationship an interaction occurred, expressed as a proportion of the total duration.

$$
L = \sum_{i=1}^{n} M_i \cdot t_i \tag{1}
$$

Trust ($T$) can then be defined as the measure of loyalty relative to the total impact of a relationship. Trust and loyalty are not interchangeable, they are separate but dependent means of navigating interactions.

$$
T = \frac{L}{M_{total}} \tag{2}
$$

Let's apply these formulas to a grounded physical context to see how we can model trust:

> A friend you have known for 2 months in which you have had 5 interactions with varying magnitudes of $M = \{6, 6, 8, 5, 7\}$:
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

When shareholders vote on company decisions, they are exercising power over an entity built through years of collective effort, customer relationships, and operational history. Yet our current system treats all votes identical regardless of whether the shareholder bought yesterday or has held for decades. A hedge fund that purchased shares last week has the same voting power per share as a pension fund that has held for twenty years - despite having radically different exposure profiles to their financial decisions. This is the mathematical flaw at the heart of plutocracy - it ignores time. 

The defects trickle down even to aspects such as remuneration, organisational function and commitment is secondary to the short term quarterly and annual earnings reports when the public market's interests are prioritised. A scenario that played out at General Electronics (GE) back in 2010, where since 1987 their pension program was entirely funded by employees and contributed billions to their bottom line margin, yet CEO Jeffrey Immelt claimed it was a "drag" to the company's fiscal operations. A comment that followed ending the defined benefit plan for employees in 2012, instead replaced with 401k compensation. GE then continued to spend up to 40 billion dollars up until 2020 on stock buybacks in an attempt to increase their financials to be attractive to the general market, all while company executives received increased pay and stock. By 2018 pensions were underfunded by a factor of 22.3 billion dollars, **the largest deficit in history of the S&P 500**.  Whether you served for over three decades at the company is not relevant, whether you have managed your life around these promised incentives is not relevant, whether you were allocated shares and held is not relevant. Only the short sighted preference of the public market is.

*Therefore, how could we factor for loyalty in a capital-weighted system?*

Prior attempts in this domain simply leave time-weighting unbounded and uncompetitive[^2] simply introducing the factor of time itself is not enough. This approach creates what we call "entrenchment" where if time-weight is purely linear, the competitive gap is zero because of first mover advantage. Like human relationships, shareholders should be given a degree of authority from simply being present and allocating their stake towards a dedicated function, as they already do through idle inventory. Although that is where it is troublesome to treat public markets and governance asset demographics equally. The latter being when shares or votes are committed towards the organisation's function, the former for provisioning shares for an economic incentive. One of the major defects of plutocracy is the ambiguity of voting power, simply due to the  accessibility and continuous nature of market liquidity.

## Commitment as a trajectory

Path-dependency is defined as the vector product of a set of actions proportional to time, while having relative obscurity in organisational theory think of it as the "commitment profile" of an actor. The means of what justifies commitment is subjective, it could be simply being present, achieving milestones or through endorsement. Looking back at equation (1) for loyalty it is clear to see the parallels, failure to maintain a relationship over-time decays the impact of prior interactions therefore loyalty can be modelled as a measure of an actors ability to sustain commitment. Simply put, it measures the rate of change of conviction.

In organisations and human relationships trust is a interpersonal metric shaped by emotional biases, and yet while tenure can be subject to the same defects - it is grounded by time and provenance. Tenure is the encapsulation of trust in collaborative work environments of course with nuances, the same applies between loyalty and path-dependency providing a qualitative but open framework on the psychology of commitment. 

## History of voting theory

Many dismiss the roots of which voting theory was formalised and applied in societal politics, yet it's an important angle that helps understand the flaws of weighted voting and dynamics of collective decision-making when choreographed incorrectly. In 1946, [Lionel Penrose](https://en.wikipedia.org/wiki/Lionel_Penrose) proposed a new method for voting demoted as the square-root method, unfortunately to not much reception although its inception marked a turning point; saturating concentrations in power but respecting broad representation. It wasn't until 1954 when Penrose's theory would be validated further, when the Noble prize winner [Lloyd Shapley](https://en.wikipedia.org/wiki/Lloyd_Shapley) and [Martin Shubik](https://en.wikipedia.org/wiki/Martin_Shubik) theorised a metric to quantify the influence of voting power through combinatorial and probabilistic methods. Known as the Shapley-Shubik index[^3] it changed how we can understanding voting power and influence in any governing system, its first real thought-provoking application was an analysis regarding the UN security council[^4], Shapley and Shubik showed how the US veto clause effectively disenfranchised all members states.

![New York Times 1991 Nassau County Board Lawsuit](assets/img/posts/i/nyt-1991-nassau-county.jpg "New York Times 1991 Nassau County Board Lawsuit")

In what is now clearly a pivotal point in time when it comes to game theory and politics, consumer advocate [John F. Banzhaf III](https://en.wikipedia.org/wiki/John_Banzhaf) was inspired by the work of Lloyd and co, upon realising the skew of power when it came to Nassau county board governance. Instead of accusations, used cold cut mathematics through devising the Banzhaf power index[^5] to prove the disparity in representation of member townships due to weighted vote scoring. This followed by perusing legal action against the board, which in 1991 was deemed successful enacting remodeling of the county's governance to a more democratic and egalitarian one-member one-vote model.

Fast forward to the 21st century and there has been a reignition in voting inspired from the foundations of the square-root method proposed by Penrose and validated by Shapley thus inspired Banzhaf. Yet more commonly acclaimed  being derived from the mechanism design work of that of "point-purchase" systems and the optimal voting rules[^6].  Quadratic Voting (QV) proposed by [Weyl](https://en.wikipedia.org/wiki/Glen_Weyl) and [Posner](https://en.wikipedia.org/wiki/Eric_Posner) in 2017, uses the square-root function to replicate a "quadratic" cost in multi-balloted voting systems. It's only flaw is the need for Sybil protection, as it ultimately fails from the exponential advantage from what is called a splitting attack[^7]. Much is the reason why it has failed to be integral to capital markets and has shown more function in democratic settings, such as in the case of Taiwan's digital ministry running pilots for budget ballots in 2018 further validating the benefits of the square root method in voting theory.

## Polycentrism 

Looking back at Kula ring and comparing it to corporate governance, the ancient exchange system had multiple degrees of authority such as time and commitment (accumulated through reciprocity; gifts, trading, marital agreements etc), whereas shareholder governance only has capital to equate to power. In 1951 [Micheal Polanyi](https://en.wikipedia.org/wiki/Michael_Polanyi) theorised the thesis of polycentrism; which is defined as systems with multiple groups or centres of authority. On the contrary to monocentrism, where there is only one.

Plutocracy's intent was always polycentrism but often falls ill to the strifes of capitalism that it never achieves a flat organisational structure and usually conforms to a traditional hierarchy. The Kula ring is inherently polycentric not only because of the multiple degrees a participant must enact to gain authority but because the system is governed and established by the dozen of archipelago chiefs, no single actor has complete control or can shift the dynamics of the system alone.

_What if time itself determines the balance between quadratic and linear weighting?_

This is exactly the basis behind a new voting model for capital markets we designed known as [Polycentric voting](), where time is introduced as an additional domain for authority past capital. 

Following in precedent to the flaws of past attempts, we introduce the concept of **effective time weight**; a capital-weighted time metric, resulting in dynamics where the time weight is rebalanced on subsequent deposits and preserved on reductions. 

Within this we propose a new quantitative model for modelling **tenure**, by formalising path-dependency as the variance of an actors time weight we get a distinctive map of the trajectory of their commitment, with  tenure being the slope of that curvature. Providing a distinctive profile of stakeholders behaviour regardless of stake.

To showcase the model we define four strategies; Singleton, Splitting, Dynamic and Sequential - each with a final share amount of 10,000 and varied inventory schedules:

<picture>
  <source srcset="assets/img/posts/i/pv_strategy_breakdown_dark.svg" media="(prefers-color-scheme: dark)">
  <img src="assets/img/posts/i/pv_strategy_breakdown_light.svg">
  <center>
  <p><i>Strategy breakdown</i></p>
  </center>
</picture>

To saturate concentrations of power lacking tenure, we introduce a novel weighting mechanism; a composite weight composed of "quadratic" and linear ruling that deviates with time to purely linear, labelled as the **power ratio**. Resulting in the temporal saturation of larger stakeholders and broader representation of the sum parts to those of the smaller. 

Furthermore, we apply logarithmic time for depreciating returns across the voting power curve at key stages, complimentary to what is denoted as **power tranches**; which are normalised phases of growth which create tiered demographics to promote coalition building for polycentric decision-making.


<picture>
  <source srcset="assets/img/posts/i/pv_strategies_dark.svg" media="(prefers-color-scheme: dark)">
  <img src="assets/img/posts/i/pv_strategies_light.svg">
  <center>
  <p><i>Strategy benchmark</i></p>
  </center>
</picture>



A byproduct of the temporal but composite weighting scheme is Sybil resistance, as observed under the Splitting strategy, an adversary that attempts to game the system undertakes immense opportunity cost so much so that if it fails they are left with **a 50% loss in aggregated voting power** in comparison to the Singleton strategy. 

## Collectivism

For things to improve there must be collective thought and action, if all stayed quiet neither would change, focal acts as the centre of action and thought in the digital era.

Expect further commentary and publications, support us at [ops@focal.org]()

[^1]: Malinowski, *Argonauts of the Western Pacific* (1922)
[^2]: Berger, D.J., Solomon, S.D. & Benjamin, A., *Tenure Voting and the U.S. Public Company*, The Business Lawyer, Vol. 72, No. 2 (2017)
[^3]: Shapley & Shubik, *A Method for Evaluating the Distribution of Power in a Committee System* (1954)
[^4]: Shapley & Shubik, *The Application of Power Indexes to World Politics* (1954) 
[^5]: Banzhaf, *Weighted Voting Doesn't Work* (1965)
[^6]: Hylland & Zeckhauser, *The Efficient Allocation of Public Goods* (1979); Ledyard & Palfrey, *The Provision of Public Goods Under Alternative Electoral Institutions* (1994)
[^7]: Douceur, J.R., *The Sybil Attack* (2002), Microsoft Research

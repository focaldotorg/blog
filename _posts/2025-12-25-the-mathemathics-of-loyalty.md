---
layout: post
author: "Samuel J. Gosling"
title: "The Mathemathics of Loyalty"
image: /assets/img/kula-ring-map.jpg
permalink: the-mathemathics-of-loyalty
description: "Reciprocity, capital markets and shareholder governance"
date: "25/12/2025"
---

Humans since the dawn of early intelligence have operated or retaliated through relationships derived from reoccurring experiences. The measure of how frequent, and how positive or negative interactions are, shape what we call **trust** between parties of any relationship, which function constructively through reciprocity. 

![The Kula ring](/assets/img/kula-ring-map.jpg)

Take the **Kula ring** of the Trobriand Islands as example, **a ceremonial exchange system** where shell necklaces (soulava) travel clockwise and shell armbands (mwali) move counterclockwise through an archipelago of island communities in the Solomon sea. The objects themselves hold little utilitarian value; their worth lies entirely in the relationships they represent. A chief who receives a soulava is expected to reciprocate with a mwali - not immediately, but eventually. The delay is crucial. It creates obligation, builds anticipation, and tests commitment over time. 

The system only functions because participants trust that gifts given today will be reciprocated months or years hence. What the Kula ring demonstrates is that loyalty and trust are not instantaneous - they are accumulated through repeated cycles, weighted by time. A trading partner who has participated faithfully for decades carries far more social capital of one that hasn't. The system inherently recognises that time, levity and history matter and yet, many would argue "trust" cannot be quantified.

$$
S = \sum_{i=1}^{n} M_i \tag{1}
$$

If we are to identify the core pillars of what constitutes ***trust ($T$)*** it would equate to: ***magnitude ($M$)*** the positive or negative social impact an interaction has on a recipient, ***interactions ($n$)***  the total number of trust-affecting events since acquaintance, and ***time ($t$)***  the duration since acquaintance. Using algebraic arithmetic, this gives us the equation: 

$$
T =  S t
$$

Let's apply these formulas to a grounded relatable physical context to see how we can model trust.

###### Scenario: The New Friend

For the 2-month friendship, let's assume you've had 5 positive interactions so far (meeting, hanging out, they lent you \$500, etc.) with magnitudes of $M = 6, 6, 8, 5, 7$.

$T = t \cdot \sum_{i=1}^{n} M_i$

$T = 0.17 \times (6 + 6 + 8 + 5 + 7)$

$T = 5.44$

Now they ask for the loan, and you lend them the money for them to __repay you on time__.

- Magnitude of honoring trust: $M_{new} = +7 $
- Impact: $\Delta T = M_{new} \times T_{current} \times t = (+7) \times 5.44 \times 0.17 = \textbf{+6.47} $
- New total trust: $T_{new} = T + \Delta T = 5.44 + 6.47 = \textbf{11.91} $

The friends **trust more than doubles (119% increase)** as the relationship is young with modest accumulated trust, this significant positive action has a meaningful but proportionate impact. The friendship is strengthened substantially, establishing a foundation for future trust.

------

Consider __corporate governance__: when shareholders vote on company decisions, they are exercising power over an entity built through years of collective effort, customer relationships, and operational history. Yet our current system treats all votes identically, regardless of whether the shareholder bought yesterday or has held for decades. A hedge fund that purchased shares last week has the same voting power per share as a pension fund that has held for twenty years—despite having radically different exposure to the long-term consequences of their decisions. This is the mathematical flaw at the heart of **plutocracy** - it ignores time. *In our trust equations, a system that only considers magnitude ($M$) and current holdings while disregarding time ($t$) and trust ($T$) will systematically favor actors with low $t$—those with minimal stake in long-term outcomes. *When a short-term investor votes to maximise quarterly earnings through layoffs or asset sales, they capture the benefits ($ΔT_{+}$ for themselves) while long-term stakeholders - employees, customers, communities and the patient investors absorb the loss.

The defects of plutoracy trickle down even to aspects such as remuneration, organisation function and commitment is secondary to the short term quarterly and annual earnings reports when the public market's interests are prioritised. A scenario that played out at General Electronics (GE) back in 2010, where since 1987 their pension program was entirely funded by employees and contributed billions to their bottom line margins yet  CEO Jeffrey Immelt claimed was a "drag" to the companies fiscal operations. A comment that was followed by ending the defined benefit plan for employees in 2012, instead replaced with 401(k) compensation. GE then continued to spend up to 40 billion dollars up until 2020 on stock buybacks in an attempt to increase their finnancials to be attractable to the general market, all while company executives recieved increased pay and stock. By 2018, pensions were underfunded by a factor of 22.3 billion dollars, **the largest deficit in the S&P 500**.  Whether you served for over three decades at the company is not relevant, whether you have managed your life around these promised incentives is not relevant, whether you were allocated shares and held is not relevant. What is, is the short sighted preference of public markets. 

*While capital-weighted voting systems are effective for economic leverage, they fail to be attractive for broad participation with rich and diverse stakeholder demographics. Simply through disenfranchising smaller actors versus the larger, so how could we factor for loyalty in a capital-weighted system? 

*Prior attempts in this domain simply leave time-weighting unbounded and uncompetitive, **simplying introducing the factor of time itself is not enough**. This approach creates what we call "entrenchment" where if time-weight is purely linear, the competitive gap is zero because of first mover advantage. Like human relationships as modelled in equation (1), shareholders should be given a degree of authority from simplying being present and allocating their stake towards a dedicated function, as they already do through idle inventory, although that is where it is troublesome to treat public markets from goverance allocatory voting demographics equal. The first being when shares or votes are commited towards the organisations function (governance) the latter for provisioning shares for an economic incentive. One of the major flaws of plutoracy is the ambiguity of voting power, simply because of the accessibility and continuous market liquidity.

Many dismiss the roots of which voting theory was formualised and applied in societal politics, yet its an important angle that helps understand the flaws of weighted voting and gravity of decision-making when governance is chreographed incorrectly. In 1946, Lionel Penrose proposed a new method to voting through what is demoted as the square-root method, unfortunately to not much reception although its inception marked a turning point; saturating concentrations in power but respecting broad representation. It wasn't until 1954 when Penrose's theory would be validated further, when the Noble prize winner Lloyd Shapley and Martin Shubik theorised a metric to quantify the influence of voting power through combinatorial and probabilistic methods. Known as the **Shapley-Shubik index** it changed how we can understanding voting power and influence in any governing system, its first real thought-provoking application was an analysis regarding the UN security council, Shapley and Shubik showed how the US veto clause effectively disenfranchised all members states.

![New York Times 1991 Nassau County Board Lawsuit](/assets/img/nyt-1991-nassau-county.jpg)

In what now is clearly a pivotal point in time when it comes to game theory and politics, consumer advocate John F. Banzhaf III was inspired by the work of Lloyd and co when he saw the skew of power when it came to Nassau county board governance. Instead of accusations, John used cold cut mathemathics through devising his own power index to prove the disparity in representation of member townships due to weighted vote scoring. This followed by persuing legal action against the board, which in 1991 was deemed successful enacting remodelling of the county's governance to a more democratic and elegetarian one-member one-vote model.

Fast forward to the 21st century and there has been a reignition in preferential voting inspired from the foundations of square-root weighting proposed by Penrose, validated by Shapley and applied by Banzhaf. 

Quadratic Voting (QV), introduced by Weyl and Posner in 2017, uses the square-root or "quadratic" method for voting weight, with a new found application for highlighting the voting minority when chreographed correctly. Its only flaw is the need for sybil protection because it ultimately fails from the exponential advantage to what is called as a "splitting attack". Much is the reason to why it has failed to be integral to capital markets and has shown more function in democratic settings, even Taiwan's digital minstry has ran pilots for budget ballots in 2018 further validating its benefits.

TODO: Callback reference to kula ring to reinforce how capital markets cannot get this right but anicent exchange systems can

**The mathematical challenge becomes clear**:

* Voting power shouldn't have a **fixed** relationship with capital and time
* Time-weighting should not be linear 
* Time-weight should be competitive through dilution
* Voting power should be evolutionary, with distinct "phases" similar to human relationships
* Sybil immunity or detterents is desirable to promote delegtory function

__What if time itself determined the balance between quadratic and linear weighting?___

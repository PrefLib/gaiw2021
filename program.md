---
layout: page
title: Program
published: true
---

## Invited Talks

**Speaker:** Michael Wooldridge, University of Oxford

**Title:** Understanding Equilibrium Properties of Multi-Agent Systems

**Abstract:** Over a twenty minute period on the afternoon 6 May 2010, the Dow Jones industrial average collapsed, at one point wiping a trillion dollars off the value of the US markets. Remarkably, the market recovered in a similarly short period of time, to nearly its position before the collapse. While the precise causes of the so-called "Flash Crash" are complex and controversial, the Flash Crash was only possible because modern international markets are multi-agent systems, in which high frequency trading agents autonomously buy and sell on timescales that are so small that they are far beyond human comprehension or control. There is no reason to believe that the 2010 Flash Crash was an isolated event: and the next one could be even bigger, with potentially devastating global consequences. The 2010 Flash Crash provides a stark illustration of something we have long known: that systems composed of large numbers of multiple interacting components can be subject to rapid, unpredictable swings in behaviour.  We urgently need to develop the theory and tools to understand such multi-agent system dynamics.
 
In this talk, I will present two very different approaches to this problem. The first views a multi-agent system as a game, in the sense of game theory, with decision-makers interacting strategically in pursuit of their goals. I describe a model we have developed in which players in such a game act in pursuit of temporal logic goals. In such a setting, the key decision problems relate to the properties of a system that hold under the assumption that players choose strategies in (Nash) equilibrium. I conclude by describing a tool, developed by DPhil student Muhammed Najib, through which we can automatically analyse the properties of such equilibria. The second approach takes a very different approach, in which we use agent-based financial models, involving very large numbers of agents, to understand specifically the factors that can contribute to Flash Crash events, and in particular the phenomenon of "contagion", where stress on one asset leads to other assets being stressed.
 
This talk will report joint work with Ani Calinescu, Julian Gutierrez, Paul Harrenstein, Muhammed Najib, James Paulin, and Giuseppe Perelli.

**Bio:** Michael Wooldridge is a Professor of Computer Science and Head of Department of Computer Science at the University of Oxford. He has been an AI researcher for more than 25 years, and has published more than 400 scientific articles on the subject. He is a Fellow of the Association for Computing Machinery (ACM), the Association for the Advancement of AI (AAAI), and the European Association for AI (EurAI). From 2014-16, he was President of the European Association for AI, and from 2015-17 he was President of the International Joint Conference on AI (IJCAI).

---

**Speaker:** Ioannis Caragiannis, Aarhus University

**Title:** Impartial selection, additive approximation guarantees, and priors

**Abstract:** We study the problem of impartial selection, a topic that lies at the intersection of computational social choice and mechanism design. The goal is to select the most popular individual among a set of community members. The input can be modelled as a directed graph, where each node represents an individual, and a directed edge indicates nomination or approval of a community member to another. An impartial mechanism is robust to potential selfish behaviour of the individuals and provides appropriate incentives to voters to report their true preferences by ensuring that the chance of a node to become a winner does not depend on its outgoing edges. The goal is to design impartial mechanisms that select a node with an in-degree that is as close as possible to the highest in-degree. Recent progress has identified impartial selection rules with optimal approximation ratios. It was noted, though, that worst-case instances are graphs with few vertices. Motivated by this fact, we propose the study of additive approximation, the difference between the highest number of nominations and the number of nominations of the selected member, as an alternative measure of quality. We present randomized impartial selection mechanisms with additive approximation guarantees of o(n), where n is the number of nodes in the input graph. We furthermore demonstrate that prior information on voters' preferences can be useful in the design of simple (deterministic) impartial selection mechanisms with good additive approximation guarantees. In this direction, we consider different models of prior information and analyze the performance of a natural selection mechanism that we call approval voting with default (AVD).

## Accepted Papers

| Authors                                                                                     | Title                                                                                 |
|---------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------|
| Leora Schmerler and Noam Hazon.                                                             | Strategic voting in negotiating teams                                                 |
| Ben Armstrong and Kate Larson.                                                              | On the Limited Applicability of Liquid Democracy                                      |
| Nimrod Talmon and Rutvik Page.                                                              | Proportionality in Committee Selection with Negative Feelings                         |
| Felix Brandt, Martin Bullinger and Anaëlle Wilczynski.                                      | Reaching Individually Stable Coalition Structures                                     |
| Patrick Lederer.                                                                            | Strategyproof Randomized Social Choice for Restricted Sets of Utility Functions       |
| Mithun Chakraborty, Ulrike Schmidt-Kraepelin and Warut Suksompong.                          | Picking Sequences and Monotonicity in Weighted Fair Division                          |
| Chenhao Wang and Qiong Liu.                                                                 | Load Balancing Game in Loss Communication Networks                                    |
| Zun Li and Michael Wellman.                                                                 | Evolution Strategies for Approximate Solution of Bayesian Games                       |
| Umang Bhaskar, Sricharan Ar and Rohit Vaish.                                                | On Approximate Envy-Freeness for Indivisible Chores and Mixed Resources               |
| Grzegorz Gawron and Piotr Faliszewski.                                                      | Using Multiwinner Voting to Search for Movies                                         |
| Dvir Gilor, Rica Gonen and Erel Segal-Halevi.                                               | Ascending-Price Mechanism for General Multi-Sided Markets                             |
| Rupert Freeman, Evi Micha and Nisarg Shah.                                                  | Two-Sided Matching Meets Fair Division                                                |
| Hadi Hosseini, Fatima Umar and Rohit Vaish.                                                 | Accomplice Manipulation of the Deferred Acceptance Algorithm                          |
| Jaelle Scheuerman, Jason Harman, Nicholas Mattei and Kristen Brent Venable.                 | Modeling Voters in Multi-Winner Approval Voting                                       |
| Hadi Hosseini and Andrew Searns.                                                            | Guaranteeing Maximin Shares: Some Agents Left Behind                                  |
| Jonathan Scarlett, Nicholas Teh and Yair Zick.                                              | For One and All: Individual and Group Fairness in the Allocation of Indivisible Goods |
| Omer Lev, Nicholas Mattei, Paolo Turrini and Stanislav Zhydkov.                             | Peer Selection with Noisy Assessments                                                 |
| Kotone Ninagawa, Yasser Mohammad and Amy Greenwald.                                         | Baseline Strategies for the ANAC Automated Negotiation League                         |
| Hanrui Zhang, Yu Cheng and Vincent Conitzer.                                                | Automated Mechanism Design for Classification with Partial Verification               |
| Steven Jecmen, Hanrui Zhang, Ryan Liu, Nihar Shah, Vincent Conitzer and Fei Fang.           | Mitigating Manipulation in Peer Review via Randomized Reviewer Assignments            |
| Scott Emmons, Caspar Oesterheld, Andrew Critch, Vincent Conitzer and Stuart Russell.        | Symmetry, Equilibria, and Robustness in Common-Payoff Games                           |
| Andrea Martin, Nicholas Mattei and Kristen Brent Venable.                                   | Behavioral Stable Marriage Problems                                                   |
| Caspar Oesterheld and Vincent Conitzer.                                                     | Decision Scoring Rules                                                                |
| Gabriel Andrade, Rafael Frongillo, Sharadha Srinivasan and Elliot Gorokhovsky.              | Graphical Economics with Resale                                                       |
| Anilesh Kollagunta Krishnaswamy, Haoming Li, David Rein, Hanrui Zhang and Vincent Conitzer. | Classification with Strategically Withheld Data                                       |
| Jonathan Wagner and Reshef Meir.                                                            | A VCG Adaptation for Participatory Budgeting                                          |
| Mehmet Ismail.                                                                              | The strategy of conflict and cooperation                                              |

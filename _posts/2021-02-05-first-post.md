---
layout: post
published: true
comments: false
title: Designing Incentives for Heterogeneous Researchers
date: 2021-02-05
categories: blog
tags: [Econ]
description: The first post!
math: true
---
This paper is by Nathan Yoder (R&R Journal of Political Economy, 2021). 

The link is available [here](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=3154143).

<h5>Model</h5>

<ul>
<li> Information procurement: A decision-maker contracts with a researcher whose cost of running experiments is private information. </li>
<ul>
<li> Bayesian persuasion: the sender's payoff is specified by a contract.</li>
<li> Contracting in a setting with adverse selection: the low-cost researcher may mimic the high-cost for ``high compensation'', so there is efficiency loss. </li>
</ul>
<li> The cost of an experiment is assumed to be posterior-separable, and multiplicatively separable with the researcher's type. $C(\tau,\theta)=E_{\tau}[\theta \cdot c(p)]$, where $c(p)=H(p_{0})-H(p)$ represents the reduction in the measure of uncertainty $H$.</li>
<li> The contract can be based on either the experiment (methods-based) or the realized posterior (results-based). Results-based contracts are more realistic, ex. the researcher could be rewarded according to the journal publication. It is not easy to contract on the research method, a full experiment containing various counterfacturals. </li>
</ul>

<h5> Results (Binary states) </h5>

<ul>
<li> Methods-based Contracts
<ul>
<li> There exists an optimal methods-based contract that implements a binary, feasible, Blackwell-monotone experiment choice function. (binary: at most two signals; feasible: the cost of experiments doesn't explode; Blackwell-monotone: a lower-cost researcher chooses Blackwell-more informative experiment.) </li>
<li> No distortion at the top and garbling everywhere. (Maskin & Riley, 1984)</li>
</ul>
</li>
<li> Results-based Contracts
 <ul>
<li> Any binary, feasible, Blackwell-monotone experiment choice function can be implemented with a result-based contract. We can construct such contract ``outwards'' (from the highest-cost to the lowest-cost). </li>
<li> Results-based implementation requires Blackwell-monotonicity. </li>
</ul>
 </li>
</ul>

<h5> Insights </h5>
<ul>
 <li> A comparative statics result is the key: More convex information design problems have Blackwell-more informative solutions. (Quasisupermodularity needs not hold here)
 </li>
</ul>

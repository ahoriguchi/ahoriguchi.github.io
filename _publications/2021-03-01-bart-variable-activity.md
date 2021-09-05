---
title: "Assessing variable activity for Bayesian regression trees"
collection: publications
permalink: /publication/2021-03-01-bart-variable-activity
excerpt: 'This paper is about assessing variable activity for BART via computing Soboĺ indices, which turns out to be quite fast and accurate.'
date: 2021-03-01
venue: 'Reliability Engineering & System Safety'
citation: 'Horiguchi, Akira, Matthew T. Pratola, and Thomas J. Santner. (2021). &quot;Assessing variable activity for Bayesian regression trees.&quot; <i>Reliability Engineering & System Safety</i>. 207.'
---

[html](https://www.sciencedirect.com/science/article/pii/S0951832020308784?casa_token=zZN4netuXQgAAAAA:Z5PhU4OgvG86aGQWutVWw35R_u56SeHKGjx2w2go8IlUg-BPWaBDfzVrrDykuWhRB15X7OaX8cI) 
[arXiv](https://arxiv.org/abs/2005.13622)

Bayesian Additive Regression Trees (BART) are non-parametric models that can capture complex exogenous variable effects. In any regression problem, it is often of interest to learn which variables are most active. Variable activity in BART is usually measured by counting the number of times a tree splits for each variable. Such one-way counts have the advantage of fast computations. Despite their convenience, one-way counts have several issues. They are statistically unjustified, cannot distinguish between main effects and interaction effects, and become inflated when measuring interaction effects. An alternative method well-established in the literature is Soboĺ indices, a variance-based global sensitivity analysis technique. However, these indices often require Monte Carlo integration, which can be computationally expensive. This paper provides analytic expressions for Soboĺ indices for BART posterior samples. These expressions are easy to interpret and are computationally feasible. Furthermore, we will show a fascinating connection between first-order (main-effects) Soboĺ indices and one-way counts. We also introduce a novel ranking method, and use this to demonstrate that the proposed indices preserve the Soboĺ-based rank order of variable importance. Finally, we compare these methods using analytic test functions and the En-ROADS climate impacts simulator.


<!-- Horiguchi, Akira, Matthew T. Pratola, and Thomas J. Santner. (2021). "Assessing variable activity for Bayesian regression trees." <i>Reliability Engineering & System Safety</i>. 207. -->

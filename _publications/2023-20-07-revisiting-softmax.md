---
title: "Revisiting Softmax for Uncertainty Approximation in Text Classification"
authors: "Andreas Nugaard Holm, <strong>Dustin Wright</strong>, and Isabelle Augenstein"
collection: publications
permalink: /publication/2023-20-07-revisiting-softmax
excerpt: 'We analyze the tradeoffs between softmax and MC dropout for uncertainty estimation'
date: 2023-07-20
venue: 'Information'
paperurl: 'https://www.mdpi.com/2078-2489/14/7/420'
bibtex: '@article{holm2023revisiting,
author = {Holm, Andreas Nugaard and Wright, Dustin and Augenstein, Isabelle},
title = {{Revisiting Softmax for Uncertainty Approximation in Text Classification}},
journal = {Information},
volume = {14},
year = {2023},
number = {7},
article-number = {420},
url = {https://www.mdpi.com/2078-2489/14/7/420},
issn = {2078-2489},
doi = {10.3390/info14070420}
}'
---
Uncertainty approximation in text classification is an important area with applications in domain adaptation and interpretability. One of the most widely used uncertainty approximation methods is Monte Carlo (MC) dropout, which is computationally expensive as it requires multiple forward passes through the model. A cheaper alternative is to simply use a softmax based on a single forward pass without dropout to estimate model uncertainty. However, prior work has indicated that these predictions tend to be overconfident. In this paper, we perform a thorough empirical analysis of these methods on five datasets with two base neural architectures in order to identify the trade-offs between the two. We compare both softmax and an efficient version of MC dropout on their uncertainty approximations and downstream text classification performance, while weighing their runtime (cost) against performance (benefit). We find that, while MC dropout produces the best uncertainty approximations, using a simple softmax leads to competitive, and in some cases better, uncertainty estimation for text classification at a much lower computational cost, suggesting that softmax can in fact be a sufficient uncertainty estimate when computational resources are a concern.

[Download paper here](https://www.mdpi.com/2078-2489/14/7/420)

#[View code](https://github.com/allenai/scientific-claim-generation)

Recommended bibtex: 

```
@article{holm2023revisiting,
author = {Holm, Andreas Nugaard and Wright, Dustin and Augenstein, Isabelle},
title = {{Revisiting Softmax for Uncertainty Approximation in Text Classification}},
journal = {Information},
volume = {14},
year = {2023},
number = {7},
article-number = {420},
url = {https://www.mdpi.com/2078-2489/14/7/420},
issn = {2078-2489},
doi = {10.3390/info14070420}
}
```

---
title: "Multi-View Knowledge Distillation from Crowd Annotations for Out-of-Domain Generalization"
authors: "<strong>Dustin Wright</strong>, and Isabelle Augenstein"
collection: publications
permalink: /publication/2023-23-05-multi-view-knowledge-distillation
excerpt: 'We perform an empirical analysis and propose new methods for aggregating labels from crowd annotations'
date: 2023-05-23
venue: 'arxiv'
paperurl: 'https://arxiv.org/pdf/2212.09409.pdf'
bibtex: '@inproceedings{wright2022multi,
title={{Multi-View Knowledge Distillation from Crowd Annotations for Out-of-Domain Generalization}},
author={Wright, Dustin and Augenstein, Isabelle},
journal = {arXiv preprint arXiv:2212.09409},
year = 2023
}'
---
Selecting an effective training signal for tasks in natural language processing is difficult: expert annotations are expensive, and crowdsourced annotations may not be reliable. At the same time, recent work in NLP has demonstrated that learning from a distribution over labels acquired from crowd annotations can be effective. However, there are many ways to acquire such a distribution, and the performance allotted by any one method can fluctuate based on the task and the amount of available crowd annotations, making it difficult to know a priori which distribution is best. This paper systematically analyzes this in the outof-domain setting, adding to the NLP literature which has focused on in-domain evaluation, and proposes new methods for acquiring soft-labels from crowd-annotations by aggregating the distributions produced by existing methods. In particular, we propose to aggregate multiple-views of crowd annotations via temperature scaling and finding their JensenShannon centroid. We demonstrate that these aggregation methods lead to the most consistent performance across four NLP tasks on out of-domain test sets, mitigating fluctuations in performance from the individual distributions. Additionally, aggregation results in the most consistently well-calibrated uncertainty estimation. We argue that aggregating different views of crowd-annotations is an effective and minimal intervention to acquire soft-labels which induce robust classifiers despite the inconsistency of the individual soft-labeling methods.

[Download paper here](https://arxiv.org/pdf/2212.09409.pdf)

#[View code](https://github.com/allenai/scientific-claim-generation)

Recommended bibtex: 

```
@inproceedings{wright2022multi,
title={{Multi-View Knowledge Distillation from Crowd Annotations for Out-of-Domain Generalization}},
author={Wright, Dustin and Augenstein, Isabelle},
journal = {arXiv preprint arXiv:2212.09409},
year = 2023
}
```

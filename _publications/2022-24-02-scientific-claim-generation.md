---
title: "Generating Scientific Claims for Zero-Shot Scientific Fact Checking"
authors: "<strong>Dustin Wright</strong>, David Wadden, Kyle Lo, Bailey Kuehl, Arman Cohan, Isabelle Augenstein, and Lucy Lu Wang"
collection: publications
permalink: /publication/2022-24-02-scientific-claim-generation
excerpt: 'We develop methods for generating and evaluating atomic, valid scientific claims from citation texts.'
date: 2022-06-28
venue: 'ACL'
paperurl: 'https://arxiv.org/pdf/2203.12990.pdf'
bibtex: '@inproceedings{wright2022generating,
title={{Generating Scientific Claims for Automatic Scientific Fact Checking}},
author={Wright, Dustin and Wadden, David and Lo, Kyle and Kuehl, Bailey and Augenstein, Isabelle and Wang, Lucy Lu },
booktitle = {Proceedings of ACL},
publisher = {Association for Computational Linguistics},
year = 2022
}'
image: '/images/claim-generation.png'
---
Automated scientific fact checking is difficult due to the complexity of scientific language and a lack of significant amounts of training data, as annotation requires domain expertise. To address this challenge, we propose scientific claim generation, the task of generating one or more atomic and verifiable claims from scientific sentences, and demonstrate its usefulness in zero-shot fact checking for biomedical claims. We propose CLAIMGEN-BART, a new supervised method for generating claims supported by the literature, as well as KBIN, a novel method for generating claim negations. Additionally, we adapt an existing unsupervised entity-centric method of claim generation to biomedical claims, which we call CLAIMGEN-ENTITY. Experiments on zero-shot fact checking demonstrate that both CLAIMGEN-ENTITY and CLAIMGEN-BART, coupled with KBIN, achieve up to 90% performance of fully supervised models trained on manually annotated claims and evidence. A rigorous evaluation study demonstrates significant improvement in generated claim and negation quality over existing baselines.

[Download paper here](https://arxiv.org/pdf/2203.12990.pdf)

[View code](https://github.com/allenai/scientific-claim-generation)

Recommended bibtex: 

```
@inproceedings{wright2022generating,
  title={{Generating Scientific Claims for Automatic Scientific Fact Checking}},
  author={Wright, Dustin and Wadden, David and Lo, Kyle and Kuehl, Bailey and Augenstein, Isabelle and Wang, Lucy Lu },
  booktitle = {Proceedings of ACL},
  publisher = {Association for Computational Linguistics},
  year = 2022
}
```

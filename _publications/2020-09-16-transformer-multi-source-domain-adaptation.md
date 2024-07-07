---
title: "Transformer Based Multi-Source Domain Adaptation"
authors: "<strong>Dustin Wright</strong> and Isabelle Augenstein"
collection: publications
permalink: /publication/2020-09-16-transformer-multi-source-domain-adaptation
excerpt: 'We demonstrate that when using large pretrained transformer models, mixture of experts methods can lead to significant gains in domain adaptation settings while domain adversarial training does not. We provide evidence that such models are relatively robust across domains, making homogenous predictions despite being fine-tuned on different domains.'
date: 2020-09-16
venue: 'EMNLP'
paperurl: 'https://arxiv.org/abs/2009.07806'
bibtex: '@inproceedings{wright2020transformer,
title={{Transformer Based Multi-Source Domain Adaptation}},
author={Dustin Wright and Isabelle Augenstein},
booktitle = {Proceedings of EMNLP},
publisher = {Association for Computational Linguistics},
year = 2020
}'
image: '/images/tbmsda.jpeg'
---
In practical machine learning settings, the data on which a model must make predictions often come from a different distribution than the data it was trained on. Here, we investigate the problem of unsupervised multi-source domain adaptation, where a model is trained on labelled data from multiple source domains and must make predictions on a domain for which no labelled data has been seen. Prior work with CNNs and RNNs has demonstrated the benefit of mixture of experts, where the predictions of multiple domain expert classifiers are combined; as well as domain adversarial training, to induce a domain agnostic representation space. Inspired by this, we investigate how such methods can be effectively applied to large pretrained transformer models. We find that domain adversarial training has an effect on the learned representations of these models while having little effect on their performance, suggesting that large transformer-based models are already relatively robust across domains. Additionally, we show that mixture of experts leads to significant performance improvements by comparing several variants of mixing functions, including one novel mixture based on attention. Finally, we demonstrate that the predictions of large pretrained transformer based domain experts are highly homogenous, making it challenging to learn effective functions for mixing their predictions.

[View paper here](https://www.aclweb.org/anthology/2020.emnlp-main.639.pdf)

[Download code here](https://github.com/copenlu/xformer-multi-source-domain-adaptation)

Recommended bibtex: 

```
@inproceedings{wright2020transformer,
  title={Transformer Based Multi-Source Domain Adaptation},
  author={Dustin Wright and Isabelle Augenstein},
  booktitle = {Proceedings of EMNLP},
  publisher = {Association for Computational Linguistics},
  year = 2020
}
```

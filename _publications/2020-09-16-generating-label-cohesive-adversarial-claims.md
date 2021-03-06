---
title: "Generating Label Cohesive and Well-Formed Adversarial Claims"
authors: "Pepa Atanasova* and <strong>Dustin Wright</strong>* and Isabelle Augenstein"
collection: publications
permalink: /publication/generating-label-cohesive-adversarial-claims
excerpt: 'We propose a novel method using universal adversarial triggers and GPT-2 to generate difficult adversarial claims for fact checking models which preserve label direction and are semantically coherent, showing that such generated claims easily fool fact checking models.'
date: 2020-09-16
venue: 'EMNLP'
bibtex: '@inproceedings{atanasova2020generating,
title={{Generating Label Cohesive and Well-Formed Adversarial Claims}},
author={Pepa Atanasova and Dustin Wright and Isabelle Augenstein},
booktitle = {Proceedings of EMNLP},
publisher = {Association for Computational Linguistics},
year = 2020
}'
featured: true
image: '/images/adversarial_fact_checking.jpeg'
---
Adversarial attacks reveal important vulnerabilities and flaws of trained models. One potent type of attack are universal adversarial triggers, which are individual n-grams that, when appended to instances of a class under attack, can trick a model into predicting a target class. However, for inference tasks such as fact checking, these triggers often inadvertently invert the meaning of instances they are inserted in. In addition, such attacks produce semantically nonsensical inputs, as they simply concatenate triggers to existing samples. Here, we investigate how to generate adversarial attacks against fact checking systems that preserve the ground truth meaning and are semantically valid. We extend the HotFlip attack algorithm used for universal trigger generation by jointly minimizing the target class loss of a fact checking model and the entailment class loss of an auxiliary natural language inference model. We then train a conditional language model to generate semantically valid statements, which include the found universal triggers. We find that the generated attacks maintain the directionality and semantic validity of the claim better than previous work.

[View paper here](https://www.aclweb.org/anthology/2020.emnlp-main.256.pdf)

[Download code here](https://github.com/copenlu/fever-adversarial-attacks)

Recommended bibtex: 

```
@inproceedings{atanasova2020generating,
  title={Generating Label Cohesive and Well-Formed Adversarial Claims},
  author={Pepa Atanasova and Dustin Wright and Isabelle Augenstein},
  booktitle = {Proceedings of EMNLP},
  publisher = {Association for Computational Linguistics},
  year = 2020
}
```

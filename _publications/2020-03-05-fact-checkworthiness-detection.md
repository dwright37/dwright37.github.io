---
title: "Fact check-worthiness detection as positive unlabelled learning"
collection: publications
permalink: /publication/2020-03-05-fact-checkworthiness-detection
excerpt: 'We show that when performing the task of claim check-worthiness detection, positive-unlabelled learning helps across multiple domains. Additionally, we highlight key similarities and differences in check-worthiness detection datasets.'
date: 2020-03-05
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/pdf/2003.02736'
bibtex: '@article{wright2020fact,
  title={Fact check-worthiness detection as positive unlabelled learning},
  author={Wright, Dustin and Augenstein, Isabelle},
  journal={arXiv preprint arXiv:2003.02736},
  year={2020}
}'
---
A critical component of automatically combating misinformation is the detection of fact check-worthiness, ie determining if a piece of information should be checked for veracity. There are multiple isolated lines of research which address this core issue: check-worthiness detection from political speeches and debates, rumour detection on Twitter, and citation needed detection from Wikipedia. What is still lacking is a structured comparison of these variants of check-worthiness, as well as a unified approach to them. We find that check-worthiness detection is a very challenging task in any domain, because it both hinges upon detecting how factual a sentence is, and how likely a sentence is to be believed without verification. As such, annotators often only mark those instances they judge to be clear-cut check-worthy. Our best-performing method automatically corrects for this, using a variant of positive unlabelled learning, which learns when an instance annotated as not check-worthy should in fact have been annotated as being check-worthy. In applying this, we outperform the state of the art in two of the three domains studied for check-worthiness detection in English.

[Download paper here](https://arxiv.org/pdf/2003.02736)

Recommended bibtex: 

```
@article{wright2020fact,
  title={Fact check-worthiness detection as positive unlabelled learning},
  author={Wright, Dustin and Augenstein, Isabelle},
  journal={arXiv preprint arXiv:2003.02736},
  year={2020}
}
```

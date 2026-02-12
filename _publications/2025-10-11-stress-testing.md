---
title: "Stress Testing Factual Consistency Metrics for Long-Document Summarization"
authors: "Zain Muhammad Mujahid, <strong>Dustin Wright</strong>, Isabelle Augenstein"
collection: publications
permalink: /publication/2025-10-11-stress-testing
excerpt: 'We demonstrate that factuality metrics are brittle for evaluating query focused long document summarization.'
date: 2025-11-10
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2511.07689'
bibtex: '@article{mujahid2025stress,
  title={{Stress Testing Factual Consistency Metrics for Long-Document Summarization}},
  author={Mujahid, Zain Muhammad and Wright, Dustin and Augenstein, Isabelle},
  journal={arXiv preprint arXiv:2511.07689},
  year={2025}
}'
---
Evaluating the factual consistency of abstractive text summarization remains a significant challenge, particularly for long documents, where conventional metrics struggle with input length limitations and long-range dependencies. In this work, we systematically evaluate the reliability of six widely used reference-free factuality metrics, originally proposed for short-form summarization, in the long-document setting. We probe metric robustness through seven factuality-preserving perturbations applied to summaries, namely paraphrasing, simplification, synonym replacement, logically equivalent negations, vocabulary reduction, compression, and source text insertion, and further analyze their sensitivity to retrieval context and claim information density. Across three long-form benchmark datasets spanning science fiction, legal, and scientific domains, our results reveal that existing short-form metrics produce inconsistent scores for semantically equivalent summaries and exhibit declining reliability for information-dense claims whose content is semantically similar to many parts of the source document. While expanding the retrieval context improves stability in some domains, no metric consistently maintains factual alignment under long-context conditions. Finally, our results highlight concrete directions for improving factuality evaluation, including multi-span reasoning, context-aware calibration, and training on meaning-preserving variations to enhance robustness in long-form summarization. We release all code, perturbed data, and scripts required to reproduce our results at this https URL.

[Download paper here](https://arxiv.org/abs/2511.07689)

[Code and data](https://github.com/zainmujahid/metricEval-longSum)


Recommended bibtex: 

```
@article{mujahid2025stress,
  title={{Stress Testing Factual Consistency Metrics for Long-Document Summarization}},
  author={Mujahid, Zain Muhammad and Wright, Dustin and Augenstein, Isabelle},
  journal={arXiv preprint arXiv:2511.07689},
  year={2025}
}
```

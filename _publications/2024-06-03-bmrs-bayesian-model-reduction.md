---
title: "BMRS: Bayesian Model Reduction for Structured Pruning"
authors: "<strong>Dustin Wright</strong>, Christian Igel, and Raghavendra Selvan"
collection: publications
permalink: /publication/2024-06-03-bmrs-bayesian-model-reduction
excerpt: 'We derive thresholdless pruning rules for structured pruning and empirically demonstrate their automatic pruning capability.'
date: 2024-06-03
venue: 'arXiv'
paperurl: '[https://arxiv.org/abs/2406.01345](https://arxiv.org/abs/2406.01345)'
bibtex: '@inproceedings{wright2024bmrs,
      title={BMRS: Bayesian Model Reduction for Structured Pruning},
      author={Wright, Dustin and Igel, Christian and Selvan, Raghavendra},
      year={2024},
      booktitle={Neural Information Processing Systems (NeurIPS)}
}'
---
Modern neural networks are often massively overparameterized leading to high compute costs during training and at inference. One effective method to improve both the compute and energy efficiency of neural networks while maintaining good performance is structured pruning, where full network structures (e.g. neurons or convolutional filters) that have limited impact on the model output are removed. In this work, we propose Bayesian Model Reduction for Structured pruning (BMRS), a fully end-to-end Bayesian method of structured pruning. BMRS is based on two recent methods: Bayesian structured pruning with multiplicative noise, and Bayesian model reduction (BMR), a method which allows efficient comparison of Bayesian models under a change in prior. We present two realizations of BMRS derived from different priors which yield different structured pruning characteristics: 1) BMRS_N with the truncated log-normal prior, which offers reliable compression rates and accuracy without the need for tuning any thresholds and 2) BMRS_U with the truncated log-uniform prior that can achieve more aggressive compression based on the boundaries of truncation. Overall, we find that BMRS offers a theoretically grounded approach to structured pruning of neural networks yielding both high compression rates and accuracy. Experiments on multiple datasets and neural networks of varying complexity showed that the two BMRS methods offer a competitive performance-efficiency trade-off compared to other pruning methods.
[Download paper here](https://arxiv.org/abs/2406.01345)


Recommended bibtex: 

```
@inproceedings{wright2024bmrs,
      title={BMRS: Bayesian Model Reduction for Structured Pruning},
      author={Wright, Dustin and Igel, Christian and Selvan, Raghavendra},
      year={2024},
      booktitle={Neural Information Processing Systems (NeurIPS)}
}
```

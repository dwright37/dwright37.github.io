---
title: "Semi-Supervised Exaggeration Detection of Health Science Press Releases"
authors: "<strong>Dustin Wright</strong> and Isabelle Augenstein"
collection: publications
permalink: /publication/2021-11-07-exaggeration-detection
excerpt: 'We formalize and introduce a test set for exaggeration detection of health science, and propose MT-PET, an extension of Pattern Exploiting Training, to perform the task in a few-shot setting.'
date: 2021-11-07
venue: 'EMNLP'
paperurl: 'https://arxiv.org/pdf/2108.13493.pdf'
bibtex: '@inproceedings{wright2021exaggeration,
title={ {Semi-Supervised Exaggeration Detection of Health Science Press Releases} },
author={Dustin Wright and Isabelle Augenstein},
booktitle = {Proceedings of EMNLP},
publisher = {Association for Computational Linguistics},
year = 2021
}'
image: '/images/exaggeration-detection.png'
---
Public trust in science depends on honest and factual communication of scientific papers. However, recent studies have demonstrated a tendency of news media to misrepresent scientific papers by exaggerating their findings. Given this, we present a formalization of and study into the problem of exaggeration detection in science communication. While there are an abundance of scientific papers and popular media articles written about them, very rarely do the articles include a direct link to the original paper, making data collection challenging, and necessitating the need for few-shot learning. We address this by curating a set of labeled press release/abstract pairs from existing expert annotated studies on exaggeration in press releases of scientific papers suitable for benchmarking the performance of machine learning models on the task. Using limited data from this and previous studies on exaggeration detection in science, we introduce MT-PET, a multi-task version of Pattern Exploiting Training (PET), which leverages knowledge from complementary cloze-style QA tasks to improve few-shot learning. We demonstrate that MT-PET outperforms PET and supervised learning both when data is limited, as well as when there is an abundance of data for the main task.

[Download paper here](https://arxiv.org/pdf/2108.13493.pdf)

[View code](https://github.com/copenlu/scientific-exaggeration-detection)

Recommended bibtex: 

```
@inproceedings{wright2021exaggeration,
    title={ {Semi-Supervised Exaggeration Detection of Health Science Press Releases} },
    author={Dustin Wright and Isabelle Augenstein},
    booktitle = {Proceedings of EMNLP},
    publisher = {Association for Computational Linguistics},
    year = 2021
}
```

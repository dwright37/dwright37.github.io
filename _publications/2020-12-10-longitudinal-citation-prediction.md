---
title: "Longitudinal Citation Prediction using Temporal Graph Neural Networks"
authors: "Andreas Nugaard Holm, Barbara Plank, <strong>Dustin Wright</strong> and Isabelle Augenstein"
collection: publications
permalink: /publication/2020-12-10-longitudinal-citation-prediction
excerpt: 'We present a method and dataset for the novel task of predicting the trajectory of citations a paper will receive over time.'
date: 2022-02-28
venue: 'AAAI 2022 Workshop on Scientific Document Understanding (SDU 2022)'
paperurl: 'https://arxiv.org/pdf/2012.05742.pdf'
bibtex: '@inproceedings{holm2022longitudinal,
title={ {Longitudinal Citation Prediction using Temporal Graph Neural Networks} },
author={Andreas Nugaard Holm and Barbara Plank and Dustin Wright and Isabelle Augenstein},
year={2022},
proceedings={AAAI 2022 Workshop on Scientific Document Understanding (SDU 2022)}
}'
featured: false
---
Citation count prediction is the task of predicting the number of citations a paper has gained after a period of time. Prior work viewed this as a static prediction task. As papers and their citations evolve over time, considering the dynamics of the number of citations a paper will receive would seem logical. Here, we introduce the task of sequence citation prediction, where the goal is to accurately predict the trajectory of the number of citations a scholarly work receives over time. We propose to view papers as a structured network of citations, allowing us to use topological information as a learning signal. Additionally, we learn how this dynamic citation network changes over time and the impact of paper meta-data such as authors, venues and abstracts. To approach the introduced task, we derive a dynamic citation network from Semantic Scholar which spans over 42 years. We present a model which exploits topological and temporal information using graph convolution networks paired with sequence prediction, and compare it against multiple baselines, testing the importance of topological and temporal information and analyzing model performance. Our experiments show that leveraging both the temporal and topological information greatly increases the performance of predicting citation counts over time.

[Download paper here](https://arxiv.org/pdf/2012.05742.pdf)


Recommended bibtex: 

```
@inproceedings{holm2022longitudinal,
title={ {Longitudinal Citation Prediction using Temporal Graph Neural Networks} },
author={Andreas Nugaard Holm and Barbara Plank and Dustin Wright and Isabelle Augenstein},
year={2022},
proceedings={AAAI 2022 Workshop on Scientific Document Understanding (SDU 2022)}
}
```

---
title: "Aggregating soft labels from crowd annotations improves uncertainty estimation under distribution shift"
authors: "<strong>Dustin Wright</strong> and Isabelle Augenstein"
collection: publications
permalink: /publication/2023-23-05-multi-view-knowledge-distillation
excerpt: 'We perform an empirical analysis and propose new methods for aggregating labels from crowd annotations'
date: 2025-06-09
venue: 'PLOS One'
paperurl: 'https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0323064'
bibtex: '@article{wright2025aggregating,
  title={{Aggregating soft labels from crowd annotations improves uncertainty estimation under distribution shift}},
  author={Wright, Dustin and Augenstein, Isabelle},
  journal={PLoS One},
  volume={20},
  number={6},
  pages={e0323064},
  year={2025},
  publisher={Public Library of Science San Francisco, CA USA}
}'
---
Selecting an effective training signal for machine learning tasks is difficult: expert annotations are expensive, and crowd-sourced annotations may not be reliable. Recent work has demonstrated that learning from a distribution over labels acquired from crowd annotations can be effective both for performance and uncertainty estimation. However, this has mainly been studied using a limited set of soft-labeling methods in an in-domain setting. Additionally, no one method has been shown to consistently perform well across tasks, making it difficult to know a priori which to choose. To fill these gaps, this paper provides the first large-scale empirical study on learning from crowd labels in the out-of-domain setting, systematically analyzing 8 soft-labeling methods on 4 language and vision tasks. Additionally, we propose to aggregate soft-labels via a simple average in order to achieve consistent performance across tasks. We demonstrate that this yields classifiers with improved predictive uncertainty estimation in most settings while maintaining consistent raw performance compared to learning from individual soft-labeling methods or taking a majority vote of the annotations. We additionally highlight that in regimes with abundant or minimal training data, the selection of soft labeling method is less important, while for highly subjective labels and moderate amounts of training data, aggregation yields significant improvements in uncertainty estimation over individual methods. 

[Code can be found here](https://github.com/copenlu/aggregating-crowd-annotations-ood)

[Download paper here](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0323064)

Recommended bibtex: 

```
@article{wright2025aggregating,
  title={{Aggregating soft labels from crowd annotations improves uncertainty estimation under distribution shift}},
  author={Wright, Dustin and Augenstein, Isabelle},
  journal={PLoS One},
  volume={20},
  number={6},
  pages={e0323064},
  year={2025},
  publisher={Public Library of Science San Francisco, CA USA}
}
```

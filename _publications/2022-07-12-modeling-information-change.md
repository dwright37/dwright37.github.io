---
title: "Modeling Information Change in Science Communication with Semantically Matched Paraphrases"
authors: "<strong>Dustin Wright</strong>*, Jiaxin Pei*, David Jurgens, and Isabelle Augenstein"
collection: publications
permalink: /publication/2022-07-12-modeling-information-change
excerpt: 'We develop a new dataset and models for measuring information change in science communication, providing improved performance on scientific evidence retrieval and several large scale analyses of science communication.'
date: 2022-12-07
venue: 'EMNLP'
paperurl: 'https://arxiv.org/pdf/2210.13001.pdf'
bibtex: '@article{wright2022modeling,
      title={ {Modeling Information Change in Science Communication with Semantically Matched Paraphrases} },
      author={Wright, Dustin and Jiaxin, Pei and Jurgens, David and Augenstein, Isabelle},
      year={2022},
      booktitle = {Proceedings of EMNLP},
      publisher = {Association for Computational Linguistics},
      year = 2022
}'
image: '/images/information-change.png'
featured: true
---
Whether the media faithfully communicate scientific information has long been a core issue to the science community. Automatically identifying paraphrased scientific findings could enable large-scale tracking and analysis of information changes in the science communication process, but this requires systems to understand the similarity between scientific information across multiple domains. To this end, we present the SCIENTIFIC PARAPHRASE AND INFORMATION CHANGE DATASET (SPICED), the first paraphrase dataset of scientific findings annotated for degree of information change. SPICED contains 6,000 scientific finding pairs extracted from news stories, social media discussions, and full texts of original papers. We demonstrate that SPICED poses a challenging task and that models trained on SPICED improve downstream performance on evidence retrieval for fact checking of real-world scientific claims. Finally, we show that models trained on SPICED can reveal large-scale trends in the degrees to which people and organizations faithfully communicate new scientific findings.

[Download paper here](https://arxiv.org/pdf/2210.13001.pdf)

## Code, models, and data

We've released all of the code, models, and data for the project to help with further research on NLP for understanding science communication. The code can be found [here](https://github.com/copenlu/scientific-information-change), the sentence-transformers model [here](https://huggingface.co/copenlu/spiced), and the dataset [here](https://huggingface.co/datasets/copenlu/spiced). We've additionally released a lightweight python package [scientific-information-change](https://pypi.org/project/scientific-information-change/), which can be used to measure the information matching score (IMS) between scientific sentences. You can download the package as follows:

```
pip install scientific-information-change
```


Recommended bibtex: 

```
@article{wright2022modeling,
      title={ {Modeling Information Change in Science Communication with Semantically Matched Paraphrases} },
      author={Wright, Dustin and Jiaxin, Pei and Jurgens, David and Augenstein, Isabelle},
      year={2022},
      booktitle = {Proceedings of EMNLP},
      publisher = {Association for Computational Linguistics},
      year = 2022
}
```

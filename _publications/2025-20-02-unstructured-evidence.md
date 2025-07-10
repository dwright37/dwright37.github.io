---
title: "Unstructured Evidence Attribution for Long Context Query Focused Summarization"
authors: "<strong>Dustin Wright</strong>, Zain Muhammad Mujahid, Lu Wang, Isabelle Augenstein, David Jurgens"
collection: publications
permalink: /publication/2025-20-02-unstructured-evidence
excerpt: 'We propose to generate arbitrary length evidence for long context query focused summarization and introduce a novel dataset to train models to perform this task.'
date: 2025-20-02
venue: 'arxiv'
paperurl: 'https://arxiv.org/abs/2502.14409'
bibtex: '@article{wright2025unstructured,
  author       = {Dustin Wright and
                  Zain Muhammad Mujahid and
                  Lu Wang and
                  Isabelle Augenstein and
                  David Jurgens},
  title        = {{Unstructured Evidence Attribution for Long Context Query Focused Summarization}},
  journal      = {CoRR},
  volume       = {abs/2502.14409},
  year         = {2025},
  url          = {https://doi.org/10.48550/arXiv.2502.14409},
  doi          = {10.48550/ARXIV.2502.14409}
}'
featured: True
---
Large language models (LLMs) are capable of generating coherent summaries from very long contexts given a user query. Extracting and properly citing evidence spans could help improve the transparency and reliability of these summaries. At the same time, LLMs suffer from positional biases in terms of which information they understand and attend to, which could affect evidence citation. Whereas previous work has focused on evidence citation with predefined levels of granularity (e.g. sentence, paragraph, document, etc.), we propose the task of long-context query focused summarization with unstructured evidence citation. We show how existing systems struggle to generate and properly cite unstructured evidence from their context, and that evidence tends to be "lost-in-the-middle". To help mitigate this, we create the Summaries with Unstructured Evidence Text dataset (SUnsET), a synthetic dataset generated using a novel domain-agnostic pipeline which can be used as supervision to adapt LLMs to this task. We demonstrate across 5 LLMs of different sizes and 4 datasets with varying document types and lengths that LLMs adapted with SUnsET data generate more relevant and factually consistent evidence than their base models, extract evidence from more diverse locations in their context, and can generate more relevant and consistent summaries.

[Download paper here](https://arxiv.org/abs/2502.14409)


Recommended bibtex: 

```
@article{wright2025unstructured,
  author       = {Dustin Wright and
                  Zain Muhammad Mujahid and
                  Lu Wang and
                  Isabelle Augenstein and
                  David Jurgens},
  title        = {{Unstructured Evidence Attribution for Long Context Query Focused Summarization}},
  journal      = {CoRR},
  volume       = {abs/2502.14409},
  year         = {2025},
  url          = {https://doi.org/10.48550/arXiv.2502.14409},
  doi          = {10.48550/ARXIV.2502.14409}
}
```

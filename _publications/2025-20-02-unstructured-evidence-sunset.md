---
title: "Unstructured Evidence Attribution for Long Context Query Focused Summarization"
authors: "<strong>Dustin Wright</strong>, Zain Muhammad Mujahid, Lu Wang, Isabelle Augenstein, David Jurgens"
collection: publications
permalink: /publication/2025-20-02-unstructured-evidence-sunset
excerpt: 'We propose the task of unstructured evidence attribution for long context query focused summarization and generate a synthetic dataset (SUnsET) to improve model performance on it.'
date: 2025-02-20
venue: 'arXiv'
paperurl: 'https://arxiv.org/abs/2502.14409'
bibtex: '@misc{wright2025unstructuredevidenceattributionlong,
      title={{Unstructured Evidence Attribution for Long Context Query Focused Summarization}},
      author={Dustin Wright and Zain Muhammad Mujahid and Lu Wang and Isabelle Augenstein and David Jurgens},
      year={2025},
      eprint={2502.14409},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2502.14409},
}'
---
Large language models (LLMs) are capable of generating coherent summaries from very long contexts given a user query. Extracting and properly citing evidence spans could help improve the transparency and reliability of these summaries. At the same time, LLMs suffer from positional biases in terms of which information they understand and attend to, which could affect evidence citation. Whereas previous work has focused on evidence citation with predefined levels of granularity (e.g. sentence, paragraph, document, etc.), we propose the task of long-context query focused summarization with unstructured evidence citation. We show how existing systems struggle to generate and properly cite unstructured evidence from their context, and that evidence tends to be "lost-in-the-middle". To help mitigate this, we create the Summaries with Unstructured Evidence Text dataset (SUnsET), a synthetic dataset generated using a novel domain-agnostic pipeline which can be used as supervision to adapt LLMs to this task. We demonstrate across 5 LLMs of different sizes and 4 datasets with varying document types and lengths that LLMs adapted with SUnsET data generate more relevant and factually consistent evidence than their base models, extract evidence from more diverse locations in their context, and can generate more relevant and consistent summaries.

[Download paper here](https://arxiv.org/abs/2502.14409)

[Code and data](https://github.com/dwright37/unstructured-evidence-sunset)


Recommended bibtex: 

```
@misc{wright2025unstructuredevidenceattributionlong,
      title={{Unstructured Evidence Attribution for Long Context Query Focused Summarization}},
      author={Dustin Wright and Zain Muhammad Mujahid and Lu Wang and Isabelle Augenstein and David Jurgens},
      year={2025},
      eprint={2502.14409},
      archivePrefix={arXiv},
      primaryClass={cs.CL},
      url={https://arxiv.org/abs/2502.14409},
}
```

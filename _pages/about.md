---
permalink: /
title: "Bio"
excerpt: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**I'm on the academic and industry research job market! Please reach out if you know of opportunities.**

I'm currently a Danish Data Science Academy postdoctoral fellow visiting the [BlaBlaBlab](https://blablablab.si.umich.edu/) at the University of Michigan. My research centers around the following mission: I want to make the world's knowledge **reliable** and **accessible**. This includes [real-world knowledge](https://aclanthology.org/2020.emnlp-main.256/), [scientific knowledge](https://aclanthology.org/2022.emnlp-main.117.pdf), and [diverse human knowledge](https://aclanthology.org/2020.emnlp-main.639/). The methods I use come from machine learning and natural language processing. **Reliability** is concerned with the [factuality](https://aclanthology.org/2022.acl-long.175/) and [faithfulness](https://arxiv.org/abs/2402.12431) of different types of knowledge, as well as ensuring that ML systems themselves are [safe and interpretable](https://arxiv.org/abs/2406.19238). **Accessibility** is concerned with making ML systems which process different types of knowledge both [efficient](https://arxiv.org/abs/2406.01345) and [sustainable](https://arxiv.org/abs/2309.02065).

Previously I was a postdoc in the [Saints Lab](https://github.com/saintslab) working on sustainable AI, and did my PhD with [CopeNLU](https://copenlu.github.io/) where I worked on automated fact checking, automatic understanding and analysis of science communication, and domain adaptation. I received my master's degree from University of California, San Diego, and have worked at IBM Research and the Allen Institute for Artificial Intelligence on the Semantic Scholar project. I also write sometimes on [substack](https://dustinwright.substack.com/). Outside of science I like making music and playing table top role-playing games and rhythm games.

News
========
- (26/09/2024) Our paper [BMRS: Bayesian Model Reduction for Structured Pruning](https://dustinbwright.com/publication/2024-06-03-bmrs-bayesian-model-reduction) was accepted to NeurIPS as a spotlight paper!

- (20/09/2024) Our paper [Revealing Fine-Grained Values and Opinions in Large Language Models](https://dustinbwright.com/publication/2024-07-02-revealing-fine-grained-values) was accepted to EMNLP Findings!

- (03/07/2024) Our paper [Efficiency is Not Enough: A Critical Perspective of Environmentally Sustainable AI](https://arxiv.org/abs/2309.02065) was accepted to [Communications of the ACM](https://cacm.acm.org/)!

- (05/05/2024) Started a research stay in the [BlaBlaBlab](https://blablablab.si.umich.edu/) at the University of Michigan with David Jurgens, working on long-context summarization

- (20/04/2024) Our paper [Understanding Fine-grained Distortions in Reports of Scientific Findings](https://arxiv.org/abs/2402.12431) was accepted to ACL findings!

- (15/01/2024) I've started my two year [Danish Data Science Academy](https://ddsa.dk/) postdoctoral fellowship

- (20/07/2023) "Modeling Information Change in Science Communication with Semantically Matched Paraphrases" received an honorable mention (top 5 submission) at the International Conference on Computational Social Science!

- (25/06/2023) I was awarded a two year postdoc fellowship from the [Danish Data Science Academy](https://ddsa.dk/) to work on NLP for science communication!

- (01/02/2023) Started a postdoc at University of Copenhagen in the [Saints Lab](https://github.com/saintslab) working on sustainable machine learning

- (06/10/2022) "Modeling Information Change in Science Communication with Semantically Matched Paraphrases" is accepted to EMNLP 2022!

- (15/03/2022) Gave an invited talk about science communication and misinformation detection at Elsevier

- (24/02/2022) One paper accepted to ACL on generating scientific claims for zero-shot scientific fact checking! This work was done during my internship at AI2

- (21/01/2022) Gave an invited talk about exaggeration detection in science for Search Engines Amsterdam

- (01/09/2021) Our paper on few shot learning for exaggeration detection in science is accepted to EMNLP 2021

- (02/08/2021) One paper published in Findings of ACL

- (01/06/2021) Started an internship at [AI2](https://allenai.org/) with Lucy Wang at Semantic Scholar on scientific claim generation

- (01/03/2021) Gave a talk at ETH Zürich about cite-worthiness detection.

- (15/09/2020) 2 main conference and 1 Findings paper accepted to EMNLP 2020. [Announcement thread](https://twitter.com/dustin_wright37/status/1305875978405711872?s=20)

- (19/07/2020) New website is now live!

- (08/07/2020) We hosted a series of person-limited meetups at the University of Copenhagen to view the live sessions of [ACL](https://acl2020.org/), with plenty of interesting discussions and good company :smile:

- (05/03/2020) Preprint of our work on claim check-worthiness detection (w/ [Isabelle Augenstein](https://isabelleaugenstein.github.io/)) is now available: [https://arxiv.org/pdf/2003.02736.pdf](https://arxiv.org/pdf/2003.02736.pdf)

- (01/10/2019) Started my PhD in natural language processing and machine learning at the University of Copenhagen

Press
=====
- [Feature on Montreal AI Ethics Blog](https://montrealethics.ai/efficiency-is-not-enough-a-critical-perspective-of-environmentally-sustainable-ai/)
- [Interview on the NVIDIA AI podcast](https://open.spotify.com/episode/16YohQJTOo0BDS9WtPRaOC?si=214e837b07dd414b)
- [Exaggeration Detector Could Lead to More Accurate Health Science Journalism](https://blogs.nvidia.com/blog/2021/10/01/exaggeration-detector/) (NVIDIA blog)
- [An NLP Approach to Exaggeration Detection in Science Journalism](https://www.unite.ai/an-nlp-approach-to-exaggeration-detection-in-science-journalism/) (unite.ai)

Featured Publications
========
{% for post in site.publications reversed %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

---
permalink: /
title: "Bio"
excerpt: "Bio"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a second year PhD student at the University of Copenhagen in the [CopeNLU group](https://copenlu.github.io/) studying natural language processing and machine learning. Specifically, my research focuses on automated fact checking, scientific language understanding, and domain adaptation. Before joining [CopeNLU](https://copenlu.github.io/) I was a research intern at IBM Research in Almaden, and received my master's degree from University of California, San Diego for work on disease name normalization, which won a [best application paper award at AKBC 2019](https://www.akbc.ws/2019/awards/). Outside of NLP I climb rocks and play dungeons and dragons :dragon_face: and dance games :arrow_left::arrow_down::arrow_up::arrow_right:.

News
========
- (15/09/2020) 2 main conference and 1 Findings paper accepted to EMNLP 2020. [Announcement thread](https://twitter.com/dustin_wright37/status/1305875978405711872?s=20)

- (19/07/2020) New website is now live!

- (08/07/2020) We hosted a series of person-limited meetups at the University of Copenhagen to view the live sessions of [ACL](https://acl2020.org/), with plenty of interesting discussions and good company :smile:

- (05/03/2020) Preprint of our work on claim check-worthiness detection (w/ [Isabelle Augenstein](https://isabelleaugenstein.github.io/)) is now available: [https://arxiv.org/pdf/2003.02736.pdf](https://arxiv.org/pdf/2003.02736.pdf)

- (01/10/2019) Started my PhD in natural language processing and machine learning at the University of Copenhagen

Featured Publications
========
{% for post in site.publications reversed %}
  {% if post.featured %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %}

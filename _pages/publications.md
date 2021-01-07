---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

**Quanyu Long**, Mingxuan Wang, Lei Li. [Generative Imagination Elevates Machine Translation](https://arxiv.org/abs/2009.09654).

Fan Yin, **Quanyu Long**, Tao Meng, Kai-Wei Chang. [On the Robustness of Language Encoders against Grammatical Errors](https://arxiv.org/abs/2005.05683). ACL 2020.

Lin Qiu, Dongyu Ru, Quanyu Long, Weinan Zhang, Yong Yu. [QA4IE: A Question Answering Based System for Document-Level General Information Extraction](https://ieeexplore.ieee.org/document/8972460). IEEE Access.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

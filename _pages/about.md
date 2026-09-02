---
permalink: /
title: "Junteng Liu"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the [HKUST NLP Group](https://hkust-nlp.github.io/), supervised by Prof. [Junxian He](https://jxhe.github.io/). I graduated from Shanghai Jiao Tong University (SJTU) in June 2024. My research focuses on natural language processing and machine learning.

## News

- **[2025]** Our paper *SynLogic: Synthesizing Verifiable Reasoning Data at Scale for Learning Logical Reasoning and Beyond* is released on arXiv.
- **[2025]** Our paper *On the Perception Bottleneck of VLMs for Chart Understanding* is released on arXiv.
- **[2024]** *On the Universal Truthfulness Hyperplane Inside LLMs* is published at EMNLP 2024.

## Education

- **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024

## Research Interests

- LLM Reasoning and Reinforcement Learning
- Hallucination in Vision-Language Models (VLM)
- LLM Truthfulness and Interpretability

## Research Experience

- **Research Intern**, MINIMAX, February 2025 – Present
- **Research Intern**, Tencent WXG, June 2024 – September 2024
- **Research Intern**, Shanghai AI Lab, June 2023 – December 2023

## Awards

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

## Publications

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

{% assign sorted_publications = site.publications | sort: 'date' | reverse %}
{% for post in sorted_publications %}
  {% include archive-single.html %}
{% endfor %}

## Contact

- **Email:** jliugi@connect.ust.hk
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://twitter.com/junteng88716710)

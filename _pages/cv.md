---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science (2024-Present), Hong Kong University of Science and Technology (HKUST), supervised by Professor Junxian He
* B.Eng. in Computer Science (2020-2024), Shanghai Jiao Tong University (SJTU)

Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Work Experience
======
* Research Intern, MINIMAX (February 2025 - Present)
* Research Intern, Tencent WXG (June 2024 - September 2024), advised by Zifei Shan
* Research Intern, Shanghai AI Lab (June 2023 - December 2023), advised by Prof. Yu Cheng

Skills
======
* Natural Language Processing (NLP)
* Machine Learning (ML)
* Large Language Models (LLM)
* Reinforcement Learning (RL)
* Vision-Language Models (VLM)
* LLM Truthfulness and Interpretability

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  </p>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  </p>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  </p>
---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
---

{% include base_path %}

# Academic Background
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024–present
* B.Eng., Shanghai Jiao Tong University, 2020–2024

# Research Experience
* Research Intern, MINIMAX (Feb 2025 – Present)
* Research Intern, Tencent WXG (Jun 2024 – Sep 2024)
* Research Intern, Shanghai AI Lab (Jun 2023 – Dec 2023)

# Research Interests
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models
* LLM Truthfulness and Interpretability

# Skills
* Natural Language Processing
* Machine Learning

# Publications
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
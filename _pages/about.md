---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm a Ph.D. student in [Computer Science at University of British Columbia](https://www.cs.ubc.ca), advised by [Vered Shwartz](https://www.cs.ubc.ca/~vshwartz/). I completed my master's at the School of Computing at KAIST, advised by [Alice Oh](https://aliceoh9.github.io).

My research centers on prosocial AI. I’m particularly interested in developing AI systems that support long-term user well-being while mitigating emerging risks such as over-reliance on AI, homogenization, and narrowing of perspectives. My work has also explored the socio-cultural intelligence of language models — studying how LLMs [reason about minds](https://aclanthology.org/2024.emnlp-main.1105/), [navigate cultural differences](https://aclanthology.org/2024.naacl-long.236/), and respond to [sensitive](https://aclanthology.org/2026.findings-eacl.327/) and [context-dependent](https://arxiv.org/abs/2509.25897) situations.

For more on my background and research, please see my [CV](https://chanijung.github.io/assets/files/cv.pdf).

## Selected Publications ([See all](/publications))

{% assign publications = site.publications | sort: "selected" %}
{% for post in publications %}
{% if post.selected != "" %}
{% include archive-short-publications.html %}
{% endif %}
{% endfor %}

## Teaching Experiences

- TA of AI and Its Social Impact ([Spring 2023](https://uilab-kaist.github.io/coe491-ai-and-society-spring-2024/))
- TA of Discrete Mathematics (Fall 2022)
- TA of Introduction to Programming (Fall 2019)


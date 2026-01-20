---
permalink: /
title: "About"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi! I'm a recent master's graduate in [School of Computing at KAIST](https://cs.kaist.ac.kr), where I was advised by [Alice Oh](https://aliceoh9.github.io). I'm currently collaborating with  [Language Technologies Institute at CMU](https://lti.cs.cmu.edu), working with [Maarten Sap](https://maartensap.com).

My research interests lie in human-centered NLP. I have focused on key yet under-explored facets of socio-cultural intelligence in language models, including cultural sensitivity, theory of mind, and question-asking abilities.

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


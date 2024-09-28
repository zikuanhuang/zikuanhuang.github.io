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
* B.E. in the Institute for Interdisciplinary Information Science, Tsinghua University (a.k.a Yao Class), 2021-2025 (estimated)
Work experience
======

* Autumn 2024: Teaching Assistant
  * Tsinghua University
  * Course: Cryptographic Protocols: Zero-Knowledge Proofs and MPC by Yifan Song
  
* Feburary to August, 2024: Research Intern
  * University of California, Santa Barbara
  * Supervisor: Prabhanjan Ananth

Awards
======
* Yao Award 2024 (Top 20% in Yao Class)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

---
layout: archive
title: 
permalink: /en/cv/
lang: en
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Physics, University of Sao Paulo, 2025 (expected)
* Research Intership Abroad (Fellowship), Fermilab, 2023
* M.S. in Physics, University of Sao Paulo, 2020
* B.S. in Physics, University of Sao Paulo, 2018


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
  


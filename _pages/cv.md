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
* Ph.D in Computer Science, Beihang University, 2016/09 - 2022/01
* M.S. in Computer Science, Beihang University, 2015/09 - 2016/09
* B.S. in English, Beijing Technology and Business University, 2011/09 - 2015/06

Work experience
======
* Associate Professor, School of Software, Beihang University, 2025/05 - Present
* PostDoc, School of Software, Beihang University, 2022/03 - 2025/05
  
Research Interests
======
* Natural Language Processing
* Knowledge Graphs
* Machine Learning

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

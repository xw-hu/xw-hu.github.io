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
* B.Eng. in Computer Science and Technology, South China University of Technology, 2016
* Ph.D. in Computer Science and Engineering, The Chinese University of Hong Kong, 2020

Work experience
======
* 2022-present: Research Scientist
  * Shanghai Artificial Intelligence Laboratory

* 2020-2022: Postdoctoral Fellow
  * The Chinese University of Hong Kong
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
<ul>{% for post in site.services %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

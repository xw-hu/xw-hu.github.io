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
  * Awardee of the Hong Kong Ph.D. Fellowship Scheme (HKPFS)
    
* Ph.D. in Computer Science and Engineering, The Chinese University of Hong Kong, 2020
  * GPA: 3.95/4.0 (rank first in All-English-Teaching Union Class)

Work Experience
======
* 2022-present: Research Scientist
  * Shanghai Artificial Intelligence Laboratory

* 2020-2022: Postdoctoral Fellow
  * The Chinese University of Hong Kong
  
Honors and Awards
======
  <ul>{% for post in site.honors %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

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
  
Services
======
<ul>{% for post in site.services %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

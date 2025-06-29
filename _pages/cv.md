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
* Ph.D in Beijing Normal University, 2019-2025
* Visiting Ph.D student in University of Toronto, 2023-2025
* B.S. in Beijing Normal University, 2015-2019
  
Skills
======
* R, Python
* Slurm cluster

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
  

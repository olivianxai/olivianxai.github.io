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
* Ph.D in Computer Science and Engineering, University of California, Santa Cruz, 2028 (expected)
* M.S. in Data Analytics, George Washington University, 2020
* B.S. in Management Information Systems, University of Delaware, 2018

Work experience
======
* 2021 - 2024: Member of Technical Staff
  * VMware
  * Next-Gen Firewall Management Plane team. 

Skills
======
* Java
* Python

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
  

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
* 2025: Agentic AI Engineer
  * ProspectIntel
  * Built a multi-agent framework

* 2021 - 2024: Member of Technical Staff
  * VMware
  * Next-Gen Firewall Management Plane team. 

* 2020 - 2021: Software Engineer/Data Analyst,
  * Verstand AI
  * Deployed ETL, Airflow DAGs on GCP

* 2020 - 2020: Data Scientist Intern
  * Mid-Atlantic Permanente Medical Group
  * Built a Natural Language Processing model classifying free text doctor notes to ICD-10 codes


Skills
======
* Java
* Python
* And many more

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
  

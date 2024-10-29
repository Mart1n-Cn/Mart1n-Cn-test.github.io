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
* Ph.D in xxx, Peking University, 2026 (expected)
* B.S. in xxx, Peking University, 2021

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * xxx University
  * Duties includes: xxx
  * Supervisor: xxx
  
Skills
======
* Skill 1
  * Sub-skill 1.1
  * Sub-skill 1.2

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
  
Service and leadership
======
* Currently signed in to 43 different slack teams

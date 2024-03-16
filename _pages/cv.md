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
* Ph.D in Information Technology, Deakin University, 2020
* M.S. in Information and Communication Engineering, Yeungnam University, 2009
* B.Eng. in Information Technology, Hanoi University of Technology, 2001

Work experience
======
* 2001: Teaching Assistant
  * Nha Trang University
  * Duties includes: Teaching Assistant

  
Skills
======
* Machine Learning and Data Science
* Programming Languages
  * Python
  * C/C++
  * C#

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
* Currently Head of Department of Software Engineering, Nha Trang University

---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

* Ph.D in Information Technology, Deakin University, Australia, 2020
* M.S. in Information and Communication Engineering, Yeungnam University, Republic of Korea, 2009
* B.Eng. in Information Technology, Hanoi University of Technology, Vietnam, 2001

## Work experience

* 2001-present: Lecturer
  * Nha Trang University, Vietnam
* 2018-2019: Teaching Assistant
  * School of Information Technology, Deakin University, Melbourne Burwood, Australia.

## Skills

* Applied Machine Learning and Data Science
  * Deep Learning
  * Pytorch
* Big Data frameworks
  * Hadoop
  * Spark
* Programming Languages
  * Python
  * C/C++
  * C#

## Publications

  <ul>
    {% for post in site.publications reversed %}
      {% include archive-single-cv.html %}
    {% endfor %}</ul>
  
## Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Service and leadership

* Currently Head of Department of Software Engineering, Nha Trang University

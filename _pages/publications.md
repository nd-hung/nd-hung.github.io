---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Hung's published papers are listed on [Google Scholars](https://scholar.google.com/citations?user=NDDWXZsAAAAJ)

{% if site.author.googlescholar %}
  <div class="wordwrap">
    Hung's published papers are listed on 
    <a href="{{https://scholar.google.com/citations?user=NDDWXZsAAAAJ}}"> Google Scholars </a> and
    <a href="{{https://www.researchgate.net/profile/Hung-Nguyen-88}}"> Research Gate </a>
  </div>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

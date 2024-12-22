---
layout: archive
title: "Press"
permalink: /press/
author_profile: true
---

Sharing is caring: Employee stock ownership plans tied to higher job satisfaction, study shows,
Canadian HR Reporter, 9/25/2024 [Link](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb](https://www.hrreporter.com/focus-areas/compensation-andbenefits/sharing-is-caring-employee-stock-ownership-plans-tied-to-higher-job-satisfaction-studyshows/388748)
Employee Stock Ownership Plans boost job satisfaction in U.S. manufacturing sector, IZA Newsroom, 9/9/2024 [Link](https://newsroom.iza.org/en/archive/research/employee-stock-ownership-plans-boost-job-satisfactionin-u-s-manufacturing-sector/)

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.press reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

---
layout: page
permalink: /publications/
title: publications
description: arranged in reverse chronological order
years: [2024, 2019, 2018, 2017, 2016]
nav: true
nav_order: 1
---
Here is a [link](https://scholar.google.com/citations?user=ljBAYdYAAAAJ&hl=en) to my Google Scholar page and [one](https://openreview.net/profile?id=~Kshiteesh_Hegde1) to my OpenReview profile.
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f {{ site.scholar.bibliography }} -q @*[year={{y}}]* %}
{% endfor %}

</div>

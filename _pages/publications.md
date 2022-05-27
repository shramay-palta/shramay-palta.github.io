---
layout: page
permalink: /publications/
title: Publications
description: publications by year in reversed chronological order.
years: [2022]
nav: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

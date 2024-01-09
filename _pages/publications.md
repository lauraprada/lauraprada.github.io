---
layout: page
permalink: /publications/
title: Research
years: [2024, 2023, 2022]
nav: true
nav_order: 4
---
<!-- _pages/research.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>


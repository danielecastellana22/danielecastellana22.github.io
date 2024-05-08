---
layout: page
permalink: /publications/
title: Publications
description: Publications in reversed chronological order.
years: [2024,2023,2022,2021,2020,2019,2018]
nav: false
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -q !@misc[year={{y}}] %}
{% endfor %}

</div>

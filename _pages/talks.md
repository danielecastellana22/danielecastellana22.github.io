---
layout: page
permalink: /talks/
title: Talks
description: Talks in reversed chronological order.
years: [2022,2021,2020,2019,2018]
nav: false
---
<!-- _pages/talks.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}

</div>

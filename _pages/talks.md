---
layout: page
permalink: /talks/
title: Invited talks
description: Invited talks in reversed chronological order.
years: [2022]
nav: false
---
<!-- _pages/talks.md -->
<div class="publications">
  
{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -q @misc[year={{y}}] %}

{% endfor %}

</div>

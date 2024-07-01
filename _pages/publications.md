---
layout: page
permalink: /research/
title: research
description: List of published and ongoing research work
years: [2022]
type: [published, other]
# type: [published]
nav: true
display_categories: [themes]
nav_order: 1
---

<!-- _pages/publications.md -->
<div class="publications">
  <!-- add research info - a bit about your intrests. -->

{%- for y in page.type %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[metatype={{y}}]* %}
{% endfor %}

</div>

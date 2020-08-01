---
layout: page
permalink: /publications/
title: publications

years: [2020]
nav: true
---

<div class="publications">

<h2 id="manuscripts--preprints">manuscripts <small>&amp;</small> preprints</h2>

{% for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

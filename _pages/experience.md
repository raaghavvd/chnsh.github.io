---
layout: page
permalink: /experience/
title: experience
nav: true
---

<div class="publications">

<ol class="bibliography">

{% for entry in site.data.experience %}
<li><div class="row"><div class="col-sm-5"><h5>{{ entry.dates }}</h5></div><div class="col-sm-7"><span class="title">{{ entry.title }}</span><a href="{{ entry.company_site }}" target="_blank"><span class="author">{{ entry.company }}</span></a></div></div></li>
{% endfor %}
</ol>
</div>

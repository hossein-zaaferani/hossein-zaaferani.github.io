---
layout: null
title: 333 داستان
---

{% assign app = site.data.projects['sisadosiosestory'] %}
<img src="/projects/{{ app.dir }}/{{ app.logo }}" width="128">
{% for link in app.links %}
<a href="{{ link.url }}" target="_blank">{{ link.name }}</a><br>
{% endfor %}
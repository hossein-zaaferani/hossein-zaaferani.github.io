---
layout: null
title: پیچک
---

{% assign app = site.data.projects['pichak'] %}
<img src="/projects/{{ app.dir }}/{{ app.logo }}">
{% for link in app.links %}
<a href="{{ link.url }}" target="_blank">{{ link.name }}</a><br>
{% endfor %}
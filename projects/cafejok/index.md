---
layout: null
title: کافه جوک
---

{% assign app = site.data.projects['cafejok'] %}
<img src="/projects/{{ app.dir }}/{{ app.logo }}">
{% for link in app.links %}
<a href="{{ link.url }}" target="_blank">{{ link.name }}</a><br>
{% endfor %}
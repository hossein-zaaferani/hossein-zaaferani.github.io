---
layout: null
title: دفترتلفن+
---

{% assign app = site.data.projects['contacts.plus'] %}
<img src="/projects/{{ app.dir }}/{{ app.logo }}">
{% for link in app.links %}
<a href="{{ link.url }}" target="_blank">{{ link.name }}</a><br>
{% endfor %}
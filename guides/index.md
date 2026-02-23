---
layout: page
title: Guides
permalink: /guides/
---

{% assign items = site.guides %}
{% for g in items %}

- [{{ g.title }}]({{ g.url }}){% if g.summary %} — {{ g.summary }}{% endif %}

{% endfor %}

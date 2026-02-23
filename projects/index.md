---
layout: page
title: Projects
permalink: /projects/
---

{% for p in site.projects %}

- [{{ p.title }}]({{ p.url }}) — {{ p.kind }} · {{ p.status }}

{% endfor %}

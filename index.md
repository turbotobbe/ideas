---
title: Projekt
description: Beskrivningar av projekt
---

Projekt som har formulerats mer eller mindre genomtänkt för att inte glömmas bort.

{% for project in site.projects %}
## {{ project.title }} - {{ project.description }}
[{{ project.url | absolute_url }}]({{ project.url | absolute_url }})
{{ project.excerpt | markdownify }}
{% endfor %}


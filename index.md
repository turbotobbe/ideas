---
title: Projekt
description: Beskrivningar av projekt
---

Här är de projekt som har kommit så långt att de är beskrivna i text.

{% for project in site.projects %}
## {{ project.title }} - {{ project.description }}
[{{ project.permalink | absolute_url }}]({{ project.permalink | absolute_url }})
{{ project.excerpt | markdownify }}
{% endfor %}

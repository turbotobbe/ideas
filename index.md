---
title: Projekt
description: Beskrivningar av projekt
---

{% for project in site.projects %}
## {{ project.title }}
[({{ project.url | absolute_url }})]
{{ project.excerpt | markdownify }}
{% endfor %}

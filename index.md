---
title: Projekt
description: Beskrivningar av projekt
---

Här är de projekt som har kommit så långt att de är beskrivna i text.

{% for project in site.projects %}
## {{ project.title }} - {{ project.description }}
[{{ project.url | absolute_url }}]({{ project.url | absolute_url }})
{{ project.excerpt | markdownify }}
{% endfor %}


---

Uppdaterad: {{ site.time | date_to_long_string }}

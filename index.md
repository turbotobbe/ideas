---
title: Projekt
description: Beskrivningar av projekt
---

{% for staff_member in site.staff_members %}
  <h2>{{ staff_member.name }} - {{ staff_member.position }}</h2>
  <p>{{ staff_member.content | markdownify }}</p>
{% endfor %}

{% for project in site.projects %}
## {{ project.title }}
({{ project.url | absolute_url }})
{{ project.excerpt | markdownify }}
{% endfor %}


## SSEP - Svenska Sol Energi Parker
[{{ "/ssep" | absolute_url }}]({{ "/ssep" | absolute_url }})

Ett projekt för att bygga stora sol energi parker i sverige.



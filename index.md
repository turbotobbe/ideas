---
title: Idéer
description: Beskrivningar av idéer
---

Idéer som har formulerats mer eller mindre genomtänkt för att inte glömmas bort.
Inget här är permanent och skall tas med en nya förnuft.

{% for ide in site.ideer %}
## {{ ide.title }} - {{ ide.description }}
[{{ ide.url | absolute_url }}]({{ ide.url | absolute_url }})
{{ ide.excerpt | markdownify }}
{% endfor %}


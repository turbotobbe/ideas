---
title: Idéer
description: Beskrivningar av idéer
---

Idéer som har formulerats mer eller mindre genomtänkt för att inte glömmas bort.
Inget här är permanent och skall tas med en nya förnuft.

{% for idea in site.ideas %}
## {{ idea.title }} - {{ idea.description }}
[{{ idea.url | absolute_url }}]({{ idea.url | absolute_url }})
{{ idea.excerpt | markdownify }}
{% endfor %}


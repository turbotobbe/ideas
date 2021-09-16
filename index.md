---
title: Projekt
description: Beskrivningar av projekt
---

{% for page in site.pages %}
## {{ page.title }}
({{ page.url | absolute_url }})
{{ post.excerpt }}
{% endfor %}

yada ....

## SSEP - Svenska Sol Energi Parker
[{{ "/ssep" | absolute_url }}]({{ "/ssep" | absolute_url }})

Ett projekt för att bygga stora sol energi parker i sverige.



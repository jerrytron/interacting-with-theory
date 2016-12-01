---
layout: page
title: Theories
order: 3
---

{% for theory in site.theories %}
## [{{theory.title}}]({{ site.url }}{{ theory.url }})
Here is a theory.
{% endfor %}
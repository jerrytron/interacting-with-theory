---
layout: page
title: Theories
---

{% for theory in site.theories %}
## [{{theory.title}}]({{ site.url }}{{ theory.url }})
Here is a theory.
{% endfor %}
---
title: Theories
---

{% for theory in site.theories %}
## [{{theory.title}}]({{ site.url }}{{ theory.url }})
![{{ theory.title }}]({{ site.url }}{{ site.image_path }}{{ theory.url | split:"/" | last }}{{ site.image_ext }}){: .align-center}


Here is a theory. {{ site.url }}{{ site.image_path }}{{ theory.url | split:"/" | last }}{{ site.image_ext }}
{% endfor %}
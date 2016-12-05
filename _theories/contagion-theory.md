---
title: Contagion Theory
subtitle: FROM MEDICINE & COMMUNICATIONS
excerpt: "Contact is provided by communication networks in contagion theories. These communication networks serve as a mechanism that exposes people, groups, and organizations to information, attitudinal messages and the behaviors of others."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/contagion-theory.jpg
    caption: "[**Credit/Source**](https://viralcontagion.wordpress.com/2012/10/05/images-from-virality-future-project-with-artists-at-uel/)"
sidebar:
    nav: "theories"
key_people:
  - name: ""
    bio: ""
citations:
  - text: "Name, Name. _Title_ City, S.T.: Publisher, Year."
---

![contagion theory](/assets/images/contagion-theory.jpg){: .align-right}
Contact is provided by communication networks in contagion theories. These communication networks serve as a mechanism that exposes people, groups, and organizations to information, attitudinal messages and the behaviors of others.

## Game Industry Inequality
The industry (and many tech industries) began with more white males, the old guard doesn’t want change, new professionals are heavily exposed and begin to share the attitudes of their superiors (and coworkers) through prolonged exposure.

## Key People
{% for person in page.key_people %}
### {{ person.name }}
{{ person.bio }}
{% endfor %}

{% capture notice-text %}
{% for cite in page.citations %}
{{ cite.text | markdownify }}
{% endfor %}
{% endcapture %}

<div class="notice--primary">
    {{ notice-text | markdownify }}
</div>

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Contagion_theories/)-->
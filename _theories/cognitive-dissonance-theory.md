---
title: Cognitive Dissonance Theory
subtitle: FROM MARKETING & PSYCHOLOGY
excerpt: "Cognitive dissonance is a communication theory adopted from social psychology. Cognitive is thinking or the mind; and dissonance is inconsistency or conflict."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/cognitive-dissonance-theory.jpg
    caption: "[**Credit/Source**](https://www.gerdleonhard.de/2015/07/14/so-loest-ein-zukunftsberater-positive-veraenderungen-aus/)"
sidebar:
    nav: "theories"
key_people:
  - name: ""
    bio: ""
citations:
  - text: "Name, Name. _Title_ City, S.T.: Publisher, Year."
---

![cognitive dissonance theory](/assets/images/cognitive-dissonance-theory.jpg){: .align-right}
Cognitive dissonance is a communication theory adopted from social psychology. The title gives the concept: cognitive is thinking or the mind; and dissonance is inconsistency or conflict. Cognitive dissonance is the psychological conflict from holding two or more incompatible beliefs simultaneously.

## Game Industry Inequality
A game developer worked on a game that has been identified as sexist in its portrayal of woman, but the individual believes themselves to have a lot of respect for women. They may convince themselves that it isn’t sexist, it’s just fun, and the offended parties are being over-sensitive.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Cognitive_Dissonance_theory/)-->
---
title: Social Identity Theory
subtitle: FROM HEALTH COMMUNICATION & EDUCATION
excerpt: "In the Social Identity Theory, a person has not one, “personal self”, but rather several selves that correspond to widening circles of group membership."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/social-identity-theory.jpg
    caption: "[**Credit/Source**](http://www.zurinstitute.com/)"
sidebar:
    nav: "theories"
key_people:
  - name: "Henri Tajfel"
    bio: "Was a British social psychologist at the University of Bristol."
  - name: "John Turner"
    bio: "Was a British social psychologist at the University of Bristol."
citations:
  - text: "Tajfel, Henri and John C Turner. _“The Social Identity Theory of Intergroup Behavior.”_ (2004):"
---

![social identity theory](/assets/images/social-identity-theory.jpg){: .align-right}
In the Social Identity Theory, a person has not one, “personal self”, but rather several selves that correspond to widening circles of group membership. Different social contexts may trigger an individual to think, feel and act on basis of his personal, family or national “level of self”.

## Game Industry Inequality
Intervention of the groupthink in players and industry leaders alike is going to be an immensely difficult task. One form of intervention that is taking place are some of the current advocates such as Anita Sarkeesian and Zoë Quinn, who are appealing both to people not traditionally pandered to as a games audience (and so potentially increasing audience with differing views), and those in the industry (or consuming it) that are open to the perspective that something is indeed rotten in the State of Denmark. There are many parties at play, but the two largest that would benefit from intervention are those involved with creating the games, and the primary consumers. Applying the framework of influences could provide great insight into how intervention can better take place, and how effective current attempts at influencing attitudes are.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Social_Identity_Theory/)-->
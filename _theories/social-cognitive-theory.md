---
title: Social Cognitive Theory
subtitle: FROM SOCIAL PSYCHOLOGY
excerpt: "The social cognitive theory explains how people acquire and maintain certain behavioral patterns, while also providing the basis for intervention strategies."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/social-cognitive-theory.jpg
    caption: "[**Credit/Source**](http://hl250wt2014.weebly.com/)"
sidebar:
    nav: "theories"
key_people:
  - name: "Neal Miller"
    bio: "Was an experimental psychologist at Yale University."
  - name: "John Dollard"
    bio: "Was an American psychologist and social scientist who taught anthropology at Yale University."
  - name: "Albert Bandura"
    bio: "Is the David Starr Jordan Professor Emeritus of Social Science in Psychology at Stanford University."
  - name: "Richard Walters"
    bio: "A grad student of Albert Bandura that developed research with him."
citations:
  - text: "Bandura, Albert and Richard H Walters. _Social Learning and Personality Development._ New York, NY: JSTOR, 1963."
  - text: 'Miller, Neal Elgar and John Dollard. "Social Learning and Imitation." (1941):'
---

![social cognitive theory]({{ site.baseurl }}/assets/images/social-cognitive-theory.jpg){: .align-right}
Social cognitive theory means to explain how people initially acquire and
subsequently maintain their patterns of behavior. It consists of a trifecta
of influence, from the current behavior factors, social factors, and environmental
factors. This state of being is constantly in flux, with each aspect influencing
the others, and all attributing to how we finally decide to manifest our behaviors.
It acknowledges just how complex our decision making is, and behavior that might
seem straightforward is actually a mess of influences internal and external. By
acknowledging the complexity it lays the groundwork for strategies to intervene
and improve the state of the problem being examined.

## Game Industry Inequality
Intervention of the groupthink in audience and industry leaders alike is an
incredibly difficult task. Each is reinforced by the existence of the other,
their own patterns up until this point, and lasting social inequalities that
lend resistance some amount of validation. One form of intervention that is
taking place are vocal advocates for equality and game criticism such as
Anita Sarkeesian and Zoë Quinn, who are appealing both to people not
traditionally pandered to as a game playing audience (and so potentially
increasing audience with differing views), and those in the industry
(or consuming it) that are open to the perspective that the current rigidity
of perspective is indeed problematic. There are many parties at play,
but the two largest that would benefit from intervention are those involved
with creating the games, and the primary consumers. Applying the framework of
influences could provide great insight into how intervention can better take
place, and how effective current attempts at influencing attitudes are.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Social_cognitive_theory/)-->
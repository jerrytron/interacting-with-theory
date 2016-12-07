---
title: Attribution Theory
subtitle: FROM COMMUNICATIONS & PSYCHOLOGY
excerpt: "Attribution theory is concerned with how individuals interpret events and how this relates to their thinking and behavior."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/attribution-theory.jpg
    caption: "[**Credit/Source**](http://mightymustangsutk.weebly.com/attribution-theory.html)"
sidebar:
    nav: "theories"
theory_intro:
  - image_path: /assets/images/attribution-theory.jpg
    alt: "attribution theory"
    title:
    excerpt: "Attribution theory is concerned with how individuals interpret events and how this relates to their thinking and behavior. Attribution theory assumes that people try to determine why people do what they do. A person seeking to understand why another person did something may attribute one or more causes to that behavior."
#url: "https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/attribution_theory/"
#btn_label: "Learn More"
key_people:
  - name: "Fritz Heider"
    bio: "An Austrian psychologist whose work was related to the Gestalt school."
  - name: "Harold Kelley"
    bio: "A social psychologist and professor of psychology at the University of California, Los Angeles."
  - name: "Bernard Weiner"
    bio: "A social psychologist and professor of psychology at the University of California, Los Angeles."
citations:
  - text: "Weiner, Bernard. _An Attributional Theory of Motivation and Emotion._ New York, NY: Springer-Verlag, 1986."
  - text: "Weiner, Bernard. _Achievement Motivation and Attribution Theory._ Morristown, NJ: General Learning Press, 1974."
---

<!--{% include feature_row id="theory_intro" type="right" %}-->

![attribution theory]({{ site.baseurl }}/assets/images/attribution-theory.jpg){: .align-right}
Attribution theory is concerned with how people try to understand the behavior
of other people, and assumes that people fundamentally seek to do so. Their
interpretation of why another person behaves the way they do relates to their
own cognitive process and behavior. When trying to understand another's behavior
we attribute cause either internally, concerning the person's personality or
something else about them, or externally, that they are influences by their
situation.

## Game Industry Inequality
It is important here to understand what this theory reveals to us about people,
especially their flaws in trying to understand the motivations of others. The
inequality of the game industry is not just about those working in it, but the
consumers as well. Also being primarily white and male, it's interesting to
witness the intensity in which they resist calls for change, especially in the
context of more diversity, more perspectives, and more thoughtful design.

A large part of this almost exclusively catered demographic doesn't see it
this way, however. Especially when voices of change are women, these adolescent
males may replay their emotional scars from growing up and see it as another
form of rejection. They attribute the criticisms of their favorite
medium as woman being too sensitive and unable to take jokes. They don't see
any external causes for why any existing games would affect anyone negatively,
so the flaw must be them.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/attribution_theory/)-->
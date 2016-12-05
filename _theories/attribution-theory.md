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

![attribution theory](/assets/images/attribution-theory.jpg){: .align-right}
Attribution theory is concerned with how individuals interpret events and how this relates to their thinking and behavior. Attribution theory assumes that people try to determine why people do what they do. A person seeking to understand why another person did something may attribute one or more causes to that behavior.

## Game Industry Inequality
Working with white males has been successful so far, and working with others has been more problematic (perhaps due to less experience due to not getting opportunities?).The primary consumers of the industry, also being overwhelmingly white and male, have continued to foster the attitude of being victims, and games being their escape. Women were mean to them! Didn’t give them any attention! They were nice guys but got NOTHING in return. Games were an outlet. Now THEY want to change them, take them away! They are too sensitive. They can’t take jokes.

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
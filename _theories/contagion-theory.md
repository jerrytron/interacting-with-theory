---
title: Contagion Theory
subtitle: FROM MEDICINE & COMMUNICATIONS
excerpt: "Contact is provided by communication networks in contagion theories. These communication networks serve as a mechanism that exposes people to information."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/contagion-theory.jpg
    caption: "[**Credit/Source**](https://viralcontagion.wordpress.com/2012/10/05/images-from-virality-future-project-with-artists-at-uel/)"
sidebar:
    nav: "theories"
key_people:
  - name: "Ronald Burt"
    bio: "A professor of Sociology and Strategy at the University of Chicago Booth School of Business."
  - name: "Noshir Contractor"
    bio: "A professor of Behavioral Science at Northwestern University."
  - name: "Eric Eisenberg"
    bio: "A professor and dean at University of South Florida."
citations:
  - text: 'Burt, Ronald S. _"Structural Holes\: The Social Structure of Competition,"_ Cambridge, MA: Harvard University Press, 1992.'
  - text: 'Contractor, Noshir S., and Eric M. Eisenberg. _"Communication networks and new media in organizations."_ Organizations and communication technology 143 (1990): 172.'
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
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
  - text: 'Burt, Ronald S. "The Social Structure of Competition," In _Structural Holes_, Cambridge, MA: Harvard University Press, 1992.'
  - text: 'Contractor, Noshir S and Eric M Eisenberg. "Communication Networks and New Media in Organizations." _Organizations and communication technology_ 143 (1990): 172.'
---

![contagion theory]({{ site.baseurl }}/assets/images/contagion-theory.jpg){: .align-right}
Contagion theory is an attempt to explain how within networks of people or
organizations you not only find common attitudes and behaviors, but also
observe a spread of those same attitudes and behaviors. The more concentrated
the people, and stronger the existing state of thinking, the more "infectious"
and easily spread their beliefs and assumptions are to neighboring connections
in their network of communication.

## Game Industry Inequality
The game industry, as with many tech based industries, was built populated by a
majority of educated, white male workers. Early attitudes about woman being less
capable or intelligent was kept alive as there was little motivation to change.
As such, even with new blood entering the industry, their superiors are often of
the _old guard_, or the protégés of them. Being in close contact with people
that all look and come from similar backgrounds as yourself is already enough
to strongly display the effect of contagion theory. When those with authority
over you also maintain these attitudes, in can be almost impossible to not start
to believe their perspective given enough time. The ill researches facts about
women, or the lack of good candidates, you might find yourself parroting despite
having never received the information from a reliable source. When you are asked
to hire someone new, they are likely to be similar to you, and as they integrate
into your team, start adopting those same views.

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
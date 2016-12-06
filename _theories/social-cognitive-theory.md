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
The social cognitive theory explains how people acquire and maintain certain behavioral patterns, while also providing the basis for intervention strategies. Evaluating behavioral change depends on the factors environment, people and behavior. SCT provides a framework for designing, implementing and evaluating programs.

## Game Industry Inequality
The industry and players have mutually enforced the application of identities on the player such as ‘Gamers’, ‘Hardcore Gamers’, or even ‘Casual Gamers’. Instead of people who play games of varying type and content, the result (especially for the former two) is a collection of people that have come to feel an entitlement toward the content they consume, to the extent of lashing out against any criticism directed at that content. As a whole, they simultaneously take pride in what they consume (as if they own some part of it, despite being only consumers), yet hold the medium back by resisting creative criticism and deep thought that in other creative mediums shows expansion and growth. Gamergate shows this taken to a new level, not just fighting against criticism of the medium, but supremacy of the white, and even more so male majority of the players and industry.

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
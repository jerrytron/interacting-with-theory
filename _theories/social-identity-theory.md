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
  - text: 'Tajfel, Henri and John C Turner. "The Social Identity Theory of Intergroup Behavior." (2004):'
---

![social identity theory]({{ site.baseurl }}/assets/images/social-identity-theory.jpg){: .align-right}
Social identity theory seeks to discover the minimal conditions required in
order for members of a group to discriminate against those outside their group
in favor of their own. Essentially, this theory proposes that we all have
multiple levels of self that correspond to the ever growing groups in which
we all identify with in some way. From family, to a sports team, or a hobby
you share. Your perception of the values a particular group might hold then
affect how you may feel or act.

## Game Industry Inequality
The industry and its audience have mutually enforced the application of
social identities on various subdivisions of the game audience, such as
‘Gamers’, ‘Hardcore Gamers’, or ‘Casual Gamers’. Instead of people who play
games of varying type, platform, difficulty, and content, the result 
(especially for the former two groups) is a collection of people that have
come to feel an entitlement toward the content they consume, to the extent of
lashing out against any criticism directed against that content. They
simultaneously take pride in what they consume (as if they own some part of
it, despite being only consumers), yet hold the medium back by resisting
creative criticism and deep thought that in other creative mediums shows
expansion and growth. Gamergate shows this taken to a new level, not just
fighting against criticism of the medium, but supremacy of the white, and
even more so male majority of the players and industry. The circular validation
within their group has made them incredibly dangerous, as can be demonstrated
by the large amounts of threats, hate speech, and attempts to make critics
and even their families feel unsafe.

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
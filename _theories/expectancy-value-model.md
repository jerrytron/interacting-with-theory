---
title: Expectancy Value Model
subtitle: FROM BEHAVIOR & MARKETING
excerpt: "According to expectancy-value theory, behavior is a function of the expectancies one has and the value of the goal toward which one is working."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/expectancy-value-model.jpg
    caption: "[**Credit/Source**](https://likesofmeblog.com/2015/07/01/motivation-theories/)"
sidebar:
    nav: "theories"
key_people:
  - name: "Martin Fishbein"
    bio: "Was social psychologist and professor at the University of Illinois."
citations:
  - text: 'Ajzen, Icek and Martin Fishbein. "Attitude-Behavior Relations: A Theoretical Analysis and Review of Empirical Research." _Psychological Bulletin_ 84, no. 5 (1977): 888–918.'
---

![expectancy model]({{ site.baseurl }}/assets/images/expectancy-value-model.jpg){: .align-right}
The expectancy model has to do with what people expect, and goals they work
toward to achieve the highest personal value. Every day we all face countless
choices, and this model expects that we will behave in such a way as to pursue
the path with the highest combination of success and personal value. It is
important, however, to keep in mind that the sources for perceived value can
be numerous and complex.

## Game Industry Inequality
When large game studios are confronted with the uniform and repetitive content
they churn out when so much variety is possible, they often point to their
demographics and how they are simply providing them exactly what they are
asking for. Their audience wants derivatives of the experiences they have
already enjoyed, as their brains have come to expect the lack of diversity in
content, and are pleased by the familiar. Unfortunately, this narrow thinking
is ignoring the fact that new expectations can be generated in order to please
existing audience, while expanding diversity of content would drastically
increase the potential audience that currently finds nothing to connect with.
If audiences are never exposed to anything new, they won't expect or ask for it.
By reaching out to existing media, using the news, journalism, and diverse
pools of content creators, they could find a well of interest in an audience
that thought the best they could get is more of the same. The content creators
themselves can be surprised at times when they get too lazy and simply expect
that cloning their own and other games will result in the same success they
have enjoyed in the past. No cycle like this lasts forever, just ask the music
industry.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Expectancy_Value_Theory/)-->
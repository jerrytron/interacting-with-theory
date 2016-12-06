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
According to expectancy-value theory, behavior is a function of the expectancies one has and the value of the goal toward which one is working. Such an approach predicts that, when more than one behavior is possible, the behavior chosen will be the one with the largest combination of expected success and value.

## Game Industry Inequality
A common cry in the industry is that the audience WANTS the unilateral content designed against what is primarily white male fantasy. Of course, if this is how they advertise, and this is what is available to play, and other audiences aren’t providing their voice because the entire industry has provided no reason to be of interest to them, why would anyone ask for anything different? If the industry begins by reaching out to more diverse audiences with news, media, content, and creators, perhaps the audience would expand their expectations.

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
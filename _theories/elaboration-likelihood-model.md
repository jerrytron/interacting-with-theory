---
title: Elaboration Likelihood Model
subtitle: FROM COMMUNICATIONS & RELATIONS
excerpt: "The ELM is based on the idea that attitudes are important because attitudes guide decisions and other behaviors."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/elaboration-likelihood-model.jpg
    caption: "[**Credit/Source**](https://commons.wikimedia.org/wiki/File:Elaboration_Likelihood_Model_Information_Graphic_of_Bias_and_Objective_Thinking.jpg)"
sidebar:
    nav: "theories"
key_people:
  - name: "Richard Petty"
    bio: "The Distinguished University Professor of Psychology at The Ohio State University."
  - name: "John Cacioppo"
    bio: "The Tiffany and Margaret Blake Distinguished Service Professor at the University of Chicago."
citations:
  - text: "Cacioppo, John T. and Richard E. Petty. “Effects of Message Repetition and Position on Cognitive Response, Recall, and Persuasion.” _Journal of Personality & Social Psychology_ 37 (1979): 97–109."
---

![elaboration likelihood model]({{ site.baseurl }}/assets/images/elaboration-likelihood-model.jpg){: .align-right}
The elaboration likelihood model is concerned with the importance of our
attitudes, which guide our decision making and other behaviors. These
attitudes are affected by two different routes of persuasive influence, the
central and peripheral. Why is one argument more persuasive than another?
Does it contain enough information and reasoning, or on simple attributes of
a situation? How we process argument meant to change our attitudes is vital
to understanding how we should structure an argument in order to change minds.
Motivated individuals are more likely to use their judgement and other mental
faculties to process an argument and be persuaded if it is sound.

## Game Industry Inequality
This theory is highly pertinent when it comes to changing the attitudes of
the most resistant group to improving the industry, the consumers themselves.
Most of them, again being white and male, have enjoyed privileges they have
little awareness of, and are afraid that something they love is going to be
taken away or destroyed. In order to get this demographic to consider the
many criticisms lobbed their way, they must first be motivated to do so, or
the reflexive antagonism will simply continue. Many feel attacked for enjoying
games that are being labeled as sexist, or white-washed. Even if an argument
is specific in labeling a particular component of a game as being sexist,
it can be difficult for someone who has attachment to the material to separate
that criticism from the piece as a whole. One partially successful form of
motivation I have witnessed is exposing the gamer demographic to highly
polished game experiences that break the mold of what they normally expect.
By engaging these groups through new works that push or break the boundaries
they have come to expect, they may over time come to desire more unique
perspectives.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Elaboration_Likelihood_Model/)-->
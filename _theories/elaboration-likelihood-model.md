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
  - text: "Cacioppo, John T. and Richard E. Petty. _“Effects of Message Repetition and Position on Cognitive Response, Recall, and Persuasion.”_ Journal of Personality & Social Psychology 37 (1979): 97–109."
---

![elaboration likelihood model](/assets/images/elaboration-likelihood-model.jpg){: .align-right}
The ELM is based on the idea that attitudes are important because attitudes guide decisions and other behaviors. While attitudes can result from a number of things, persuasion is a primary source. The model features two routes of persuasive influence: central and peripheral.

## Game Industry Inequality
How do you get people to consider their involvement in a larger social issue? How do you persuade them to reconsider (or consider at all) their position or place in a larger system and potentially change? In the game industry, even convincing designers to examine the choices they make in new projects, instead of “because that’s how we’ve always done it”. Say, allowing players to choose their player gender, or whether or not it is actually narratively consistent for a female character to be barely clothed.

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
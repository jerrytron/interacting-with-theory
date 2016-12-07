---
title: Cognitive Dissonance Theory
subtitle: FROM MARKETING & PSYCHOLOGY
excerpt: "Cognitive dissonance is a communication theory adopted from social psychology. Cognitive is thinking or the mind; and dissonance is inconsistency or conflict."
header:
    excerpt: false
    overlay_color: "#333"
    overlay_image: /assets/images/theories-banner.png
    teaser: /assets/images/cognitive-dissonance-theory.jpg
    caption: "[**Credit/Source**](https://www.gerdleonhard.de/2015/07/14/so-loest-ein-zukunftsberater-positive-veraenderungen-aus/)"
sidebar:
    nav: "theories"
key_people:
  - name: "Leon Festinger"
    bio: "A social psychologist who taught at University of Michigan, University of Minnesota, and Stanford University."
citations:
  - text: "Festinger, Leon. _A Theory of Cognitive Dissonance. Stanford,_ CA: Stanford university press, 1962."
---

![cognitive dissonance theory]({{ site.baseurl }}/assets/images/cognitive-dissonance-theory.jpg){: .align-right}
Cognitive dissonance concerns inconsistencies or conflicts of the mind. All of
us have held incompatible beliefs at one time or another, committing to a
behavior that is inconsistent with the information we have available to us.
Seatbelts were not always required when driving, so many of older generations
still refuse to wear them despite a deluge of information concerning the dangers
of not doing so, and how many lives have been lost as a result. My grandparents,
for instance, died for this very reason. When new information is introduced we
then try to reach equilibrium again and reduce dissonance. This could be through
a change in behavior, or by seeking information that reinforces our existing view.

## Game Industry Inequality
As the inequality in gender or POC within the game industry is pointed out to
people in decision making positions at game studios, one refutation is that
they aren't avoiding hiring diverse people, but they simply aren't available.
They points to statistics about how few non-white, non-male people are studying
in the related hiring fields, and how few of them apply for jobs. They misuse
existing facts in order to justify the status quo. Of course, the fact that
the percentage of diverse candidates is certainly lower, that doesn't mean
unavailable, so cannot excuse hiring none of them. It is also a question of
effort, as typically people simply reach into their nearby network, who they
already know, and so don't use the resources at their disposal to communicate
open positions, or seek a wider pool in which to choose from.

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

<!--[Theory Details](https://www.utwente.nl/cw/theorieenoverzicht/Theory%20Clusters/Interpersonal%20Communication%20and%20Relations/Cognitive_Dissonance_theory/)-->
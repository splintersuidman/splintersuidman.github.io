---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

* [‘Equivariant homotopy theory via orbits’](/files/equivariant-homotopy-theory-via-orbits-thesis-presentation.pdf) (Bachelor’s thesis presentation), Raboud University, Nijmegen, The Netherlands (28 June 2023)

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

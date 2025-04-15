---
layout: archive
title: "Talks and presentations"
permalink: /talks/
author_profile: true
---

* [‘Čech cohomology’](/files/2025-04-14-Čech-cohomology.pdf), Utrecht University, The Netherlands (14 April 2025): notes for a talk for the seminar course [_Topos Theory: Sheaf Cohomology_](https://leoguetta.github.io/student_seminar.html)
* [‘Homotopy category and Quillen functors’](/files/2024-05-24-homotopy-category-and-Quillen-functors.pdf), Raboud University, Nijmegen, The Netherlands (24 May 2024): handwritten notes for a talk for the seminar course _Advanced Seminar on Derived Categories_
* [‘Equivariant homotopy theory via orbits’](/files/equivariant-homotopy-theory-via-orbits-thesis-presentation.pdf) (Bachelor’s thesis presentation), Raboud University, Nijmegen, The Netherlands (28 June 2023)

{% if site.talkmap_link == true %}

<p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I've given a talk!</a></p>

{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single-talk.html %}
{% endfor %}

---
layout: default
title: "Blog"
---

I am a Vehicle test engineer at Oxbotica Ltd. My goal is to test and find edge cases that can fail an autonomous vehicle.

I graduated from Cambridge University with an MPhil in Engineering. My research was on modelling abrasive tyre wear in heavy vehicles.

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="Posts" %}
{% endif %}

---
layout: default
title: "Portfolio"
---

Welcome to my portfolio. Here, you'll find a collection of my projects, work samples, and achievements.

{% if site.show_excerpts %}
  {% include home.html %}
{% else %}
  {% include archive.html title="My Portfolio" %}
{% endif %}

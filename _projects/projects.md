---
layout: page
title: "Projects"
permalink: /projects/
---

{% for project in site.projects %}
  <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
  {% if project.image %}
    <img src="{{ project.image }}" alt="{{ project.title }}" style="max-width:400px;">
  {% endif %}
  {% if project.description %}
    <p>{{ project.description }}</p>
  {% endif %}
{% endfor %}

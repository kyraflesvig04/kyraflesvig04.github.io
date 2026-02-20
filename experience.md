---
layout: page
title: Experience
---

{% for item in site.experience %}
  <h2>
    <a href="{{ item.url }}">{{ item.title }}</a>
  </h2>
  <p>{{ item.description }}</p>
  <hr>
{% endfor %}

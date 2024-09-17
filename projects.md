---
layout: default
title: Projects
---

# My Projects

{% for project in site.projects %}
  <div class="project">
    <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
    <img src="{{ project.image }}" alt="{{ project.title }}">
    <p>{{ project.description }}</p>
  </div>
{% endfor %}
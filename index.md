---
title: Welcome to My Projects
layout: default
---

# My Projects
Explore my projects below:

<div class="project-grid">
  {% for project in site.data.projects %}
    <div class="project-card">
      <a href="{{ project.link }}">
        <img src="{{ project.image }}" alt="{{ project.name }}">
        <h3>{{ project.name }}</h3>
        <p>{{ project.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

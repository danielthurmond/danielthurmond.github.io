---
title: Daniel Thurmond
layout: default
---

# My Projects
Explore my projects below:

## About Me
Hi! I'm Daniel Thurmond, a digital design and VLSI enthusiast. I enjoy computer architecture, VLSI, and RTL-level digital design.  
This site showcases my projects—feel free to explore! WIP

---

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

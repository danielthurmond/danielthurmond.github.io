---
title: SiliWiki - Semiconductor Knowledge Base
layout: default
---

## About Me
Hi, I'm Daniel Thurmond, a digital design and VLSI enthusiast. The purpose of this wiki is to **share knowledge** about the **entire chip design pipeline**—from **specification to RTL, verification, physical design, GDS, fabrication, and beyond!**  

Whether you're a beginner or an experienced engineer, **feel free to explore**. This is a **work in progress (WIP)**, and is a personally maintained wiki.

---

# **Explore Semiconductor Topics Below:**
Each section covers a major phase in the **chip design and manufacturing process**.

<div class="process-grid">
  {% for topic in site.data.silicon_topics %}
    <div class="process-card">
      <a href="{{ topic.link }}">
        <img src="{{ topic.image }}" alt="{{ topic.name }}">
        <h3>{{ topic.name }}</h3>
        <p>{{ topic.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

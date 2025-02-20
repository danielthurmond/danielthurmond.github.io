---
title: Circuit Design and VLSI
layout: default
---

# Circuit Design and VLSI

This section covers:
- The RTL-to-GDS flow.
- Logic design, verification, and synthesis.
- Standard cell libraries and transistor-level design.

## **Explore Subtopics:**
Below are key concepts within this section:

<div class="subtopic-grid">
  {% for subtopic in site.data.circuit_design %}
    <div class="subtopic-card">
      <a href="{{ subtopic.link }}">
        <img src="{{ subtopic.image }}" alt="{{ subtopic.name }}">
        <h3>{{ subtopic.name }}</h3>
        <p>{{ subtopic.description }}</p>
      </a>
    </div>
  {% endfor %}
</div>

[🔙 Back to Main Page](/SiliWiki/)

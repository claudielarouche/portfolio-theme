---
layout: page
title: "Portfolio Theme Demo"
description: "A showcase of all components and styles available in the Portfolio Theme"
show_banner: true
---

# Welcome to the Portfolio Theme Demo

This is a live demonstration of the **Portfolio Theme**. Below you’ll see examples of reusable components you can include in your own Markdown files.

---

## Projects

<ul class="project-list">
{% for proj in site.projects %}
  <li><a href="{{ proj.url | relative_url }}">{{ proj.title }}</a></li>
{% endfor %}
</ul>
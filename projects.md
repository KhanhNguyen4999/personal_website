---
layout: default
title: Projects
permalink: /projects/
---

# Projects

Here are some of the projects I've worked on:

<div class="projects-grid">
{% for project in site.projects %}
  <div class="project-card">
    <h2><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h2>
    <p>{{ project.summary }}</p>
    <a href="{{ project.link }}" target="_blank">View Project →</a>
  </div>
{% endfor %}
</div>

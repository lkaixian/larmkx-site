---
layout: default
title: Projects
---

# 🗃️ Projects 
*Places where I create a problem to solve a problem*

<div class="projects-container">

  {% for project in site.projects %}
  <div class="project-card">
    <div class="project-title">{{ project.title }}</div>
    <div class="project-date">{{ project.date | date: "%B %Y" }}</div>
    <div class="project-desc">{{ project.description }}</div>
    <a href="{{ project.url }}">Read more</a>
  </div>
  {% endfor %}

</div>

---
layout: default
title: Project
---

# 🗃️ Projects 
*Places where I create a problem to solve a problem*

<ul>
  {% for post in site.projects %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

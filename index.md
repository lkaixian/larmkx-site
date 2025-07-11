---
layout: default
title: Home
---

# Hey there! Good to see you arrive in here :D

Hi! I'm an electronics engineering student.  
This site showcases my DIY projects, blog posts, and journey as I learn.

---
## 🌠 Featured
Not yet :<

---
## Latest Blog Posts
<ul>
  {% for post in site.posts limit:3 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>  
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>

[View all posts ->](/blog)

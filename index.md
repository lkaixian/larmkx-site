---
layout: default
title: Home
---

# Hey there! Good to see you arrive in here :D

Hi! I'm an electronics engineering student.  
This site showcases my DIY projects, blog posts, and journey as I learn.
*The journey of zero become hero.*
---
## 🌠 Featured (As of: Jul 2025)
### [Invoice Manager and Uploader App](/projects/invoice-scanner/)
Where you could upload invoice to the cloud with auto naming based on category chose and date chose.


**Date:** July 2025
[View Project ➜](/projects/invoice-scanner/)


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

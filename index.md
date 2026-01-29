---
layout: default
title: Home
---

## Welcome 👋

This is my personal blog where I document my journey in tech, automation, and learning by building real projects.

---

## 📝 Latest Posts

{% for post in site.posts %}
### [{{ Automation Projects}}]({{ post.url }})
*{{ post.date | date: "03 29, 2025" }}*

{{ post.excerpt }}

---
{% endfor %}



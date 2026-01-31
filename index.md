
---
layout: default
title: Home
---

# Hi, I’m Brian 👋

I write about **technology, automation, and learning in public**.

## Latest Posts
{% for post in site.posts limit:5 %}
- [{{ post.title }}]({{ post.url }})
{% endfor %}

👉 [Read all posts →](/blog/)

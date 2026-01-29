---
layout: default
title: Writing & Insights
permalink: /blog/
---

## Writing & Insights

Thoughts, tutorials, and lessons from my journey in technology, automation, and software development.

{% for post in site.posts %}
### [{{ Building My First Blog with GitHub Pages & Jekyll}}]({{ https://brianmukindi.github.io/2026/01/25/building-my-first-blog-with-github-pages-jekyll.html }})
*{{ post.date | date: "%B %d, %Y" }}*

{{ post.excerpt }}

---
{% endfor %}

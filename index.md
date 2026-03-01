---
layout: home
---

# Welcome to my blog

This is my first post written in **Markdown**.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

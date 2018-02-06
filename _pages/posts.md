---
permalink: /posts.html
layout: default
title: Posts
---

## Posts

{% for post in site.posts %}
* [{{ post.title }} ({{ post.date | date: "%-d %B %Y" }})]({{ post.url }})
{% endfor %}

---
permalink: /projects.html
layout: default
title: Projects
---

## Projects

{% for project in site.projects %}
* [{{ project.title }}]({{ project.url }})
{% endfor %}

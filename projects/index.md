---
layout: default
title: Projects
---

{% for project in site.projects %}
- {{ project.title }}
{% endfor %}

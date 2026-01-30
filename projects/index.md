---
layout: default
title: Projects
---

| Project | Themes | Status |
|---|---|---|
{% for project in site.projects %}
| [{{ project.title }}]({{ project.url }}) | {{ project.themes | join: ", " }} | {{ project.status }} |
{% endfor %

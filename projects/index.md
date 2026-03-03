---
layout: default
title: Projects
---

# Projects

Here's a collection of projects I'm working on or have completed.

{% for project in site.projects %}
  <div class="project">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.excerpt | strip_html }}</p>
  </div>
{% endfor %}
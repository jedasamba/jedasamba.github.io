---
title: Projects
icon: fas fa-diagram-project
order: 6
---

Hands-on projects and documentation covering IT support, Microsoft 365 administration, and systems work.

{% assign projects = site.categories["Projects"] %}
{% if projects.size > 0 %}
  {% for post in projects %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
  {% endfor %}
{% else %}
No projects yet — check back soon.
{% endif %}

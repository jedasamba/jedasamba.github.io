---
title: Writeups
icon: fas fa-pen
order: 5
---

Practical, honest writeups documenting real IT support and cloud systems work — not tutorials.

{% assign writeups = site.categories["Writeups"] %}
{% if writeups.size > 0 %}
  {% for post in writeups %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%b %d, %Y" }}
  {% endfor %}
{% else %}
No writeups yet — check back soon.
{% endif %}

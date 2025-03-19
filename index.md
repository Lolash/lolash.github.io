---
layout: default
title: Notatki z życia
---

<ul>
  {% for note in site.notes %}
    <li><a href="{{ note.url }}">{{ note.title }}</a></li>
  {% endfor %}
</ul>
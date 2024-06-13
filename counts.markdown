---
layout: page
title: Counts
permalink: /counts/
---

## Stacked bar charts of the election counts themselves, between local, general and European.

  <ul>
    {% for post in site.posts %}
    {% if post.categories contains "counts" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>

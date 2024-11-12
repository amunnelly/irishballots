---
layout: page
title: Oireachtas
permalink: /oireachtas/
---

## Streamgraphs of the Oireachtas broken down by House, Election and Party

  <ul>
    {% for post in site.posts %}
    {% if post.categories contains "oireachtas" %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>

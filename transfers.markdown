---
layout: page
title: Transfers
permalink: /transfers/
---

## Sankey diagrams of transfers between parties and candidates, broken down by election and constituency.

  <ul>
    {% for post in site.posts %}
    {% if post.categories contains "transfers" %}
      <li><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
      {% endif %}
    {% endfor %}
  </ul>

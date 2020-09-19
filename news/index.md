---
layout: default
title: News
nav_order: 2
---

# News

  {% for post in site.posts %}
    <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.date }}</p>
    <p>{{ post.excerpt }}</p>
    <p><a href="{{ post.url }}">more...</a></p>
  {% endfor %}

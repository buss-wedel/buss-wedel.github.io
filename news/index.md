---
layout: default
title: News
nav_order: 2
---

# News

<p>
  {% for post in site.posts %}
    <h2>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
    <p>
      {{ post.date | date_to_string }}
    </p>
    <p>
      {{ post.excerpt }}
      <a href="{{ post.url }}">more...</a>
    </p>
  {% endfor %}
</p>

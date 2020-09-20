---
layout: default
title: News
nav_order: 2
---

# News

<p>
  {% for post in site.posts %}
    <p>
      {{ post.date | date_to_string }} <a href="{{ post.url }}"><h2>{{ post.title }}</h2></a>
    <p>
    <p>
      {{ post.excerpt }}
      <a href="{{ post.url }}">more...</a>
    </p>
  {% endfor %}
</p>

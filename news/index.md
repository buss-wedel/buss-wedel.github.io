---
layout: default
title: News
nav_order: 2
---

# News

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>



<p>
  {% for post in site.posts %}
    <h2>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h2>
    <p>
      {{ post.date }}
    </p>
    <p>
      {{ post.excerpt }}
    
    <a href="{{ post.url }}">more...</a>
    </p>
  {% endfor %}
</p>

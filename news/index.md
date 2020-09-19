---
layout: default
title: News
nav_order: 2
---

# News

  {% for post in site.posts %}
    ## <a href="{{ post.url }}">{{ post.title }}</a>
    
    {{ post.date }}
    
    {{ post.excerpt }}
    
    <a href="{{ post.url }}">more...</a>
  {% endfor %}

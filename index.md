---
title: Home Page
layout: default
---

# Hello World

My personal blog on Github

I love :coffee: :pizza: and :dancer:

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.tile }}</a>
  </li>
  {% endfor %}
</ul>

---
layout: page
title: Blog
permalink: /blog/
---

The is where I am posting my blogs.

<li> 
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}

</li>

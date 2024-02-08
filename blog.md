---
layout: page
title: Blog
permalink: /blog/
---

<li class="blog-list"> 
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</li>

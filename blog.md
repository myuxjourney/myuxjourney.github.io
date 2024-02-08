---
layout: page
title: Blog
permalink: /blog/
---

<h4 class="h4-blog">The is where I am posting my blogs.</h4>
<li class="blog-list"> 
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</li>

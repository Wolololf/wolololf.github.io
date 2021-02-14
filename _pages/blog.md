---
title: Blog
navigation_weight: 2
permalink: /blog/
---

## Blog

<ul>
  {% for post in site.posts %}
  <li><a href="{{ post.url }}" class="post-preview">{{ post.title }}</a></li>
  {% endfor %}
</ul>
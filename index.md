---
layout: page
title:
tagline: A mind for Quality
---
{% include JB/setup %}

QualiMente is a professional services firm that can help you:

* build high-quality software
* build an agile team
* solve particularly-difficult performance, scalability, and reliability problems
    
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

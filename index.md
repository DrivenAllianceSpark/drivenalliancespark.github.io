---
layout: page
title: Spark
tagline: please change me
---
{% include JB/setup %}

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }} - {{post.tagline}}</a> (by {{post.author}})</li>
  {% endfor %}
</ul>
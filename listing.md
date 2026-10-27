---
layout: page
title: Post List
---


{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>Published on {{ post.date | date: "%Y/%m/%d %H:%M" }}</p>
{% endfor %}
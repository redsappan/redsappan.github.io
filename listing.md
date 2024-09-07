---
layout: page
title: Post List
---

**Index**

{% for post in site.posts %}
  <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
  <p>Published on {{ post.date | date: "%B %-d, %Y" }} by {{ post.author }}</p>
{% endfor %}
---
layout: page
title: Post List
---

**Index**

{% for post in site.posts %}
  <h2>{{ post.title }}</h2>
  <p>Published on {{ post.date | date: "%B %-d, %Y" }} by {{ post.author }}</p>
{% endfor %}
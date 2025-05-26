---
layout: default
# Blog | Simple Jekyll
title: Blog
header: Blog
summary: Where the magic happens - this is the blog!
permalink: /blog/
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  {{ post.date | date_to_string }}</p>
{% endfor %}

---
layout: default
# Blog | Simple Jekyll
header: Blog
summary: Where the magic happens - this is the blog!
link: /2025/05/25/saif.md
---

{% for post in site.posts %}
  <p><a href="{{ post.url }}">{{ post.title }}</a><br>
  {{ post.description }}<br>
  {{ post.date | date_to_string }}</p>
{% endfor %}

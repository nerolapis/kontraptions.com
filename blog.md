---
title: Blog
permalink: /blog/
---

<ul class="post-list">
{% for post in site.posts %}
  <li><time>{{ post.date | date: "%Y-%m-%d" }}</time><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

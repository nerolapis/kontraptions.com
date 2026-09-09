---
title: Welcome
---

This is **Kontraptions**, now built with Jekyll. Every page on this site is a Markdown file in the repository, and GitHub turns them into HTML on each push.

Latest from the blog:

<ul class="post-list">
{% for post in site.posts limit:5 %}
  <li><time>{{ post.date | date: "%Y-%m-%d" }}</time><a href="{{ post.url | relative_url }}">{{ post.title }}</a></li>
{% endfor %}
</ul>

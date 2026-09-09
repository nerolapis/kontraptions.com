---
title: Home
---

<section class="intro">
  <img class="avatar" src="{{ site.author.avatar | relative_url }}" alt="{{ site.author.name }}" width="128" height="128">
  <div>
    <h1>{{ site.author.name }}</h1>
    <p>{{ site.author.bio }}</p>
    <p class="links">
      {% for l in site.author.links %}{% if l.url != "" %}<a href="{{ l.url }}">{{ l.label }}</a>{% endif %}{% endfor %}
    </p>
  </div>
</section>

<h2 id="projects">Projects</h2>

<ul class="project-grid">
{% assign projects = site.projects | sort: "order" %}
{% for p in projects %}
  <li>
    <a href="{{ p.url | relative_url }}">
      <img class="{{ p.cover_style | default: 'photo' }}" src="{{ p.cover | relative_url }}" alt="{{ p.title }}" loading="lazy">
      <span class="kicker">{{ p.kind }}</span>
      <strong>{{ p.title }}</strong>
      <span class="tagline">{{ p.tagline }}</span>
    </a>
  </li>
{% endfor %}
</ul>

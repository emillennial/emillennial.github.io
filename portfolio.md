---
layout: page
title: Portfolio
subtitle: ♻️🍕💻💧💀🎮🌱🎧🍟🦷🎬✨
tags: me
---

### My Portfolio

<ul>
{% for post in site.posts %}
  {% if post.categories contains "portfolio" %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endif %}
{% endfor %}
</ul>

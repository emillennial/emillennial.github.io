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
    </li>
  {% endif %}
{% endfor %}
</ul>

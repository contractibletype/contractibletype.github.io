---
layout: page
title: Arxiu
permalink: /archive/
---

<ul>
{% for post in site.posts %}
  <li>
    {{ post.date | date: "%d/%m/%Y" }} —
    <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
  </li>
{% endfor %}
</ul>

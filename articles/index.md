---
layout: page
title: Articles
permalink: /articles/
---

<ul>
{% assign articles_sorted = site.articles | sort: "date" | reverse %}
{% for article in articles_sorted %}
  <li>
    {{ article.date | date: "%d/%m/%Y" }} —
    <a href="{{ article.url | relative_url }}">{{ article.title }}</a>
  </li>
{% endfor %}
</ul>

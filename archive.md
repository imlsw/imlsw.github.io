---
layout: overview
title:  "Posts"
permalink: /archive/
---

{% for post in site.categories.blog %}
  <li>
    <a href="{{ post.url }}">{{ post.title }} <span class="main-content-overview-date">{{ post.date | date: '%B %d, %Y' }}</span></a>
  </li>
{% endfor %}

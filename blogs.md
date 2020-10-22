---
layout: overview
title: "Geschreven"
permalink: /schrijft
---

# Geschreven
Soms schrijf ik een stukje.

<div class="overview-list">
{% for post in site.categories.blogs %}
  <li>
    <div class="overview-list-card">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </div>
  </li>
{% endfor %}
</div>

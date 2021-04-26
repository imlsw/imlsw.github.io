---
layout: overview
title: "Geschreven"
permalink: /schrijft
---

# Geschreven
Soms schrijf ik een stukje.

<div class="blog-list">
{% for post in site.categories.blogs %}
  <li>
    <a href="{{ post.url }}">
      <div class="blog-preview">
        <p class="blog-title">{{ post.title }} &nbsp;&#8594;</p>
        <p class="blog-description">{{ post.excerpt }}</p>
      </div>
    </a>
  </li>
{% endfor %}
</div>

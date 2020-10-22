---
layout: overview
title: "Gelezen"
permalink: /leest
---

# Gelezen
Ik lees veel. Mijn e-reader neem ik overal mee naartoe. Ik heb ooit in een concertpauze zitten lezen. Ja, echt. Sterker nog: het vaker dan één keer is voorgekomen. Maar dat terzijde. De boeken die ik lees houd ik bij via [Goodreads](https://goodreads.com/ilseml), maar hieronder kun je ze ook vinden.

<div class="overview-list">
{% for post in site.categories.boeken %}
  <li>
    <div class="overview-list-card">
      <a href="{{ post.url }}">{{ post.title }}</a>
    </div>
  </li>
{% endfor %}
</div>

---
layout: overview
title: "Notities"
permalink: /notes
intro: "Af en toe schrijf ik een stukje*. Hieronder vind je een verzameling van zaken die —wat mij beteft— het daglicht aan kunnen."
previous-page-title: "Home"
previous-page-url: "/"
next-page-title: "Over"
next-page-url: "/about"
---

<div class="all--notes">
{% for post in site.categories.blogs %}
  <li>
      <div class="cards--notes">
        <p class="cards--notes--title"><a href="{{ post.url }}"> {{ post.title }} </a></p>
        <p class="cards--notes--description">{{ post.excerpt }}</p>
      </div>
  </li>
{% endfor %}
</div>

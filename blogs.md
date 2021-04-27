---
layout: overview
title: "Geschreven"
permalink: /schrijft
---

# Geschreven
Ik ben dus echt geen held in introducties schrijven. Toch ga ik een poging wagen. Hieronder vind je een verzameling van stukjes* die ik heb geschreven waarvan ik dacht dat ze het daglicht wel mochten opzoeken.

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

<div class="notes">
  <p class="note-item">* Ik weet dat ‘stukjes’ een beetje afgezaagd klinkt, maar ik ga het ook weer geen artikelen of essays of blogs of teksten noemen. Het moet wel een beetje bij mijn ware aard blijven — en mijn ware aard zou zeggen dat het stukjes zijn om ze daarmee niet onder een vergrootglas te gooien. Want heel eerlijk: het zijn maar stukjes over mijn dagelijkse leven, geen literaire werken.</p>
</div>

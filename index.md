---
layout: home
title: "Home"
permalink: /
---

# Hoi! Leuk dat je er bent 👋

Welkom op mijn persoonlijke stukje internet. Aangenaam. Mocht je me niet kennen: mijn naam is Ilse. Oorspronkelijk kom ik uit Twente, maar na 8 verhuizingen bevind ik me momenteel in Nijmegen. Het grootste deel van de week spendeer ik aan web- en appdesigns. Daarnaast [lees ik meer dan gezond voor me is](/gelezen-in-2021), wandel ik dagelijks een kilometer of vijf, sport ik iedere ochtend en leer ik Japans voor de lol. Dat is direct ook zo’n beetje mijn leven in één paragraaf.

Als designer is het ondertussen semi-verplicht* om een online portfolio te hebben, maar dat staat me niet zo aan. Vandaar: wel een website, geen portfolio.

Om het goed te maken, schrijf ik soms stukjes. De meesten publiceer ik niet. Lang verhaal kort: ik vind mezelf soms best wel grappig**, maar dat hoeft de wereld niet te weten. Mocht je toch wat willen lezen, gaat uwe gang:

<div class="blog-list">
{% for post in site.categories.home %}
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

Dus: hoi! Kom verder. Hopelijk vind je wat leuks.

<div class="notes">
  <p class="note-item">* zegt men.</p>
  <p class="note-item">** “Je wordt met het jaar grappiger”, aldus mijn vriend. Ik weet alleen niet of hij bedoelt dat ik al grappig was en elk jaar grappiger word of dat ik nooit echt grappig ben geweest en dat hij me met deze woorden een soort van bedankt voor mijn moeite. Ik zal het eens moeten vragen. Kom ik op terug. Tussentijdse conclusie: ik moet weleens om mezelf lachen, dus ik vind mezelf soms grappig. Dat wilde ik ermee zeggen. Einde.</p>
</div>

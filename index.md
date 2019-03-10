---
layout: default
---

<style>
  main { max-width: 600px; margin: auto; }
  section { margin: 30px 0; }
</style>

Les peintures exposées sur ce site sont l'œuvre d'Isabelle de Kerchove de
Denterghem.

Artiste à toute heure, Isabelle peint surtout de l'abstrait, mais ne se
restreint pas à ce seul genre.

Elle aime varier les formats, les techniques (pinceau, couteau), et les
matières.  L'acrylique sur toile est sa prédilection, mais elle manie tout aussi
bien le papier, le lin, la soie, la roche ou même le bois.

Prenez plaisir à voyager dans son univers hétéroclite, autant qu'elle en prend à
représenter son imaginaire à travers ces toiles.

<div class="action">
  <a href="/gallery/" class="btn">Visiter la gallerie</a>
  <a href="mailto:contact@ysaflo.fr" class="btn">Contacter l'artiste</a>
</div>

<section id="news">
<h2>Actualités</h2>

{% for news in site.news -%}
  <a href="{{ news.url }}">{{ news.title | smartify }}</a>
{% endfor -%}

</section>

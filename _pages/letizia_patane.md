---
layout: page
title: Letizia Patané
permalink: /letizia_patane
---

<style>
img {
border-radius: 50%;
}
</style>
<img src="assets/images/letizia.png" width="300" height="300" align="center">

Letizia Patanè, laureata in storia dell'arte alla Sapienza, completa gli studi a Tor Vergata con un master su turismo e managment dei beni culturali.

Dopo un appassionante  e fruttifero stage presso la Fondazione Rui, consegue l'abilitazione di guida turistica di Roma.

Da sempre affine alle materie letterarie e linguistiche, decide di adottare la sua creatività e lo spirito dinamico nel campo delle arti, della musica e della cultura.

<section class="recent-posts">
<div class="section-title">
    <h2>Le mie visite guidate</h2>
</div>
<div class="row listrecent">
{% assign the_author='letizia' %}
{% for post in site.categories.Visite %}
  {% for author in post.author %}
    {% if author == the_author %}
      {% include postbox.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</div>
</section>

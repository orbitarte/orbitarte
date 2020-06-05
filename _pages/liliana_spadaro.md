---
layout: page
title: Liliana Spadaro
permalink: /liliana_spadaro
---

<style>
img {
border-radius: 50%;
}
</style>
<img src="assets/images/liliana.png" width="300" height="300" align="center">


Storica dell’arte e curatrice, con specializzazione in Arte contemporanea.
Dopo essersi laureata in Storia dell'Arte presso La Sapienza di Roma, prosegue gli studi portando a termine con successo la Scuola di Specializzazione in Beni Storico Artistici, della medesima università.

Ha collaborato con alcuni dei musei e associazioni più importanti di Roma, tra cui la Galleria Nazionale, ex GNAM, l'Archivio dei Macchiaioli, L'ufficio Mostre del Comune di Roma, e la galleria-laboratorio StudioSotterraneo.

Tra i suoi interessi principali ci sono le ultime tendenze, dal Pop Surrealism alla Street Art.

Organizzatrice di eventi e conferenze.


<section class="recent-posts">
<div class="section-title">
    <h2>Le mie visite guidate</h2>
</div>
<div class="row listrecent">
{% assign the_author='liliana' %}
{% for post in site.categories.Visite %}
  {% for author in post.author %}
    {% if author == the_author %}
      {% include postbox.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</div>
</section>

<section class="recent-posts">
<div class="section-title">
    <h2>I miei articoli</h2>
</div>
<div class="row listrecent">
{% assign the_author='liliana' %}
{% for post in site.categories.Blog %}
  {% for author in post.author %}
    {% if author == the_author %}
      {% include postbox.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</div>
</section>

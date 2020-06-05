---
layout: page
title: Greta Rocchino
permalink: /greta_rocchino
---

<style>
img {
border-radius: 50%;
}
</style>
<img src="assets/images/greta.png" width="300" height="300" align="center">


Storica dell’arte bizantina laureata alla Sapienza e accompagnatrice turistica.

Ha seguito un corso presso il Pontificio Istituto di Archeologia Cristiana e un tirocinio alla Biblioteca Casanatense ed ha fatto parte della sezione didattica del Gruppo Archeologico Romano.

Accompagnatore turistico abilitato, attualmente è operatore museale con Aditum Cultura presso il Museo dell’Alto Medioevo all’interno del Museo delle Civiltà.

I suoi interessi vanno dall’archeologia al medioevo, soprattutto del Vicino Oriente.

<section class="recent-posts">
<div class="section-title">
    <h2>Ultime Visite Guidate</h2>
</div>
<div class="row listrecent">
{% assign the_author='greta' %}
{% for post in site.categories.Visite %}
  {% for author in post.author %}
    {% if author == the_author %}
      {% include postbox.html %}
    {% endif %}
  {% endfor %}
{% endfor %}
</div>
</section>

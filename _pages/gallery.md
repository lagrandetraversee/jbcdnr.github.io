---
layout:    page
permalink: "/gallery/"
weight:    100
menutitle: Galerie
title:     Les Photos
excerpt:   Toutes les images de nos aventures au Népal.
photos: 

---

Toutes les images de notre expédition viendront ici...

<div class="album">
  {% for img in page.photos %}
   <figure>
      <img src="{{ img.file }}" />
      {% if img.caption %}
      <figcaption>{{img.caption}}</figcaption>
      {% endif %}
   </figure>
  {% endfor %}
</div>

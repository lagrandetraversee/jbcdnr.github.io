---
layout:    page
permalink: "/gallery/"
weight:    100
menutitle: Galerie
title:     Les Photos
excerpt:   Toutes les images de nos aventures au Népal.
photos: 
  - file: /3/jbstupa.jpeg
  - file: /3/land.jpeg
  - file: /3/light.jpeg
  - file: /3/mules.jpeg
  - file: /3/passflag.jpeg
  - file: /3/pierre.jpeg
  - file: /3/ricehouse.jpeg
---

<div class="album">
  {% for img in page.photos %}
   <figure>
      <img src="/media/img{{ img.file }}" />
      {% if img.caption %}
      <figcaption>{{img.caption}}</figcaption>
      {% endif %}
   </figure>
  {% endfor %}
</div>

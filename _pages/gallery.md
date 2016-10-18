---
layout:    page
permalink: "/gallery/"
weight:    100
menutitle: Galerie
title:     Les Photos
excerpt:   Toutes les images de nos aventures au Népal.
photos: 
  - file: /media/img/1/colors.jpg
  - file: /media/img/1/jb.jpg
  - file: /media/img/1/pierre.jpg
  - file: /media/img/1/stupa.jpg
  - file: /media/img/1/temple.jpg
  - file: /media/img/2/monkey.jpg
  - file: /media/img/2/stupa.jpg
  - file: /media/img/2/us.jpg
  - file: /media/img/3/bus.jpeg
  - file: /media/img/3/galere.jpeg
  - file: /media/img/3/land.jpeg
  - file: /media/img/3/farrice.jpeg
  - file: /media/img/3/uspass.jpeg
  - file: /media/img/3/ustree.jpeg
  - file: /media/img/3/butter.jpeg
  - file: /media/img/3/riz.jpeg
  - file: /media/img/3/usback.jpeg
  - file: /media/img/3/ricehouse.jpeg
  - file: /media/img/3/bridge.jpeg
  - file: /media/img/3/usfog.jpeg
  - file: /media/img/3/stone.jpeg
  - file: /media/img/3/jbstupa.jpeg
  - file: /media/img/3/ustea.jpeg
  - file: /media/img/3/light.jpeg
  - file: /media/img/3/pierre.jpeg
  - file: /media/img/3/bridgesusp.jpeg
  - file: /media/img/3/passflag.jpeg
  - file: /media/img/3/uspole.jpeg
  - file: /media/img/3/mules.jpeg
  - file: /media/img/3/cooking.jpeg
  - file: /media/img/3/stairs.jpeg
  - file: /media/img/3/toplukla.jpeg
  - file: /media/img/3/toplukla2.jpeg
---

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

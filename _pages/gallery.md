---
layout:    page
permalink: "/gallery/"
weight:    100
menutitle: Galerie
title:     Les Photos
excerpt:   Toutes les images de nos aventures au Népal.
photos: 
  - file: /media/img/1/colors.jpg
    caption: Épices en vente à l'arrière d'un vélo
  - file: /media/img/1/jb.jpg
    caption: Jean-Baptiste dans une rue commerçante et animée
  - file: /media/img/1/pierre.jpg
    caption: Pierre devant une échoppe de tissu
  - file: /media/img/1/stupa.jpg
    caption: Petit stupa bouddhiste dans la rue
  - file: /media/img/1/temple.jpg
    caption: Temple hindouiste dans Durbar Square
  - file: /media/img/2/monkey.jpg
    caption: Singes dans un parc de Kathmandu
  - file: /media/img/2/stupa.jpg
    caption: Stupa dominant Kathmandu
  - file: /media/img/2/us.jpg
    caption: Pierre et Jean-Baptiste devant Buddha
  - file: /media/img/3/bus.jpeg
    caption: Bus tout terrain 
  - file: /media/img/3/galere.jpeg
    caption: Pierre suivant péniblement une famille Sherpa
  - file: /media/img/3/farrice.jpeg
    caption: Paysage de rizières en terrasse
  - file: /media/img/3/uspass.jpeg
    caption: Premier col
  - file: /media/img/3/ustree.jpeg
  - file: /media/img/3/butter.jpeg
  - file: /media/img/3/riz.jpeg
  - file: /media/img/3/usback.jpeg
  - file: /media/img/3/ricehouse.jpeg
  - file: /media/img/3/bridge.jpeg
    caption: Pont en bambou croisé sur le chemin
  - file: /media/img/3/cold.jpeg
    caption: Cuisine du dîner
  - file: /media/img/3/usfog.jpeg
    caption: Deuxième col
  - file: /media/img/3/stone.jpeg
  - file: /media/img/3/jbstupa.jpeg
  - file: /media/img/3/ustea.jpeg
    caption: Notre devise: un col, un thé
  - file: /media/img/3/light.jpeg
  - file: /media/img/3/pierre.jpeg
  - file: /media/img/3/bridgesusp.jpeg
  - file: /media/img/3/passflag.jpeg
    caption: Col 4
  - file: /media/img/3/uspole.jpeg
    caption: Col 5
  - file: /media/img/3/mules.jpeg
  - file: /media/img/3/cooking.jpeg
  - file: /media/img/3/stairs.jpeg
  - file: /media/img/3/toplukla.jpeg
    caption: Vu sur le Kong De depuis Lukla
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

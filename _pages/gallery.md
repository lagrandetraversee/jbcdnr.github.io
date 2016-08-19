---
layout:    page
permalink: "/gallery/"
weight:    100
menutitle: Galerie
title:     La Galerie Photos
excerpt:   Toutes les images de nos aventures au Népal.
photos:    
  - file: "/media/img/mountain1.jpg"
    caption: "Superbe montagne"
  - file: "/media/img/mountain2.jpg"
  - file: "/media/img/mountain3.jpg"
  - file: "/media/img/mountain2.jpg"
    caption: "Plus de montagne"
  - file: "/media/img/mountain1.jpg"

---

Toutes les images de notre expédition...

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

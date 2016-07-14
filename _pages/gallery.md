---
layout:    page
permalink: "/gallery/"
author:    jb
weight:    100
menutitle: Gallerie
title:     La Gallerie Photo
excerpt:   Toutes les images de nos aventures au Népal.
photos:    
  - title: "/media/img/mountain1.jpg"
    caption: "Superbe montagne"
  - title: "/media/img/mountain2.jpg"
  - title: "/media/img/mountain3.jpg"
  - title: "/media/img/mountain2.jpg"
    caption: "Plus de montagne"
  - title: "/media/img/mountain1.jpg"

---

Toutes les images de notre expédition...

<div class="album">
  {% for img in page.photos %}
   <figure>
      <img src="{{ img.title }}" />
      {% if img.caption %}
      <figcaption>{{img.caption}}</figcaption>
      {% endif %}
   </figure>
  {% endfor %}
</div>

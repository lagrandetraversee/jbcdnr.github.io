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
  - file: /media/img/4/01mevillage.jpeg
  - file: /media/img/4/02pierremonk.jpeg
  - file: /media/img/4/03acclim.jpeg
  - file: /media/img/4/04usseat.jpeg
  - file: /media/img/4/05swater.jpeg
  - file: /media/img/4/06stupasun.jpeg
  - file: /media/img/4/07moon.jpeg
  - file: /media/img/4/08pierreland.jpeg
  - file: /media/img/4/09jbland.jpeg
  - file: /media/img/4/10flaglake.jpeg
  - file: /media/img/4/11gokyoview.jpeg
  - file: /media/img/4/12everest.jpeg
  - file: /media/img/4/13jbeverest.jpeg
  - file: /media/img/4/14pierreeverest.jpeg
  - file: /media/img/4/15lakeup.jpeg
  - file: /media/img/4/16lakedown.jpeg
  - file: /media/img/4/17lakeup2.jpeg
  - file: /media/img/4/18ustop.jpeg
  - file: /media/img/4/19amabc.jpeg
  - file: /media/img/4/20yak.jpeg
  - file: /media/img/4/21valley.jpeg
  - file: /media/img/4/22kern.jpeg
  - file: /media/img/4/23everest.jpeg
  - file: /media/img/4/24snow.jpeg
  - file: /media/img/4/25horizon.jpeg
  - file: /media/img/4/26amastuppa.jpeg
  - file: /media/img/5/asset-1.jpg
  - file: /media/img/5/asset-2.jpg
  - file: /media/img/5/asset-3.jpg
  - file: /media/img/5/asset-4.jpg
  - file: /media/img/5/asset-5.jpg
  - file: /media/img/5/asset-6.jpg
  - file: /media/img/5/asset-7.jpg
  - file: /media/img/5/asset-8.jpg
  - file: /media/img/5/asset-9.jpg
  - file: /media/img/6/asset-20.jpg
  - file: /media/img/6/asset-19.jpg
  - file: /media/img/6/asset-18.jpg
  - file: /media/img/6/asset-17.jpg
  - file: /media/img/6/asset-16.jpg
  - file: /media/img/6/asset-15.jpg
  - file: /media/img/6/asset-14.jpg
  - file: /media/img/6/asset-13.jpg
  - file: /media/img/6/asset-12.jpg
  - file: /media/img/6/asset-11.jpg
  - file: /media/img/6/asset-10.jpg
  - file: /media/img/6/asset-9.jpg
  - file: /media/img/6/asset-8.jpg
  - file: /media/img/6/asset-7.jpg
  - file: /media/img/6/asset-6.jpg
  - file: /media/img/6/asset-5.jpg
  - file: /media/img/6/asset-4.jpg
  - file: /media/img/6/asset-3.jpg
  - file: /media/img/6/asset-2.jpg
  - file: /media/img/6/asset-1.jpg
  - file: /media/img/6/asset.jpg
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

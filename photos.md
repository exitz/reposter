---
image:
  -  image_path:  /photos/bluehexy.jpg
     title: purplesquare.jpg bluehexy
  - image_path: /photos/box.jpg
    title:  boxy
  - image_path:: /photos/hexagon.jpg
    title:  hexagon
  - image_path: /photos/hexy.jpg
    title:  hexy
  - image_path: /photos/hyperhex.jpg
    title:  hyperhex
  - image_path:  /photos/paisley.jpg
    title: paisley
  - image_path: /photos/purlplesquare.jpg
    title:  purlplesquare
  - image_path: /photos/seethruhexy.jpg
    title: seethruhexy
  - image_path: /photos/triangle.jpg
    title: triangle
layout: default
collection: photos
---
 <ul>
{%- for image in site.photos -%}
</li>
  <a>photos/{{site.photos.image_path}}</a>
</li>
{%- endfor -%}
</ul>

---
catagory: photos
title:  "Square Pusher, Pushing Squares Gallery"
images:
  - image_path:  /photos/bluehexy.jpg
    title:  bluehexy

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

---
 <ul>
{%- for image in site.photos -%}
</li>
<img src="{{ photo.image_path}}" alt="{{image.title}}">
</li>
{%- endfor -%}
</ul>

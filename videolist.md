---
layout: default
title: video library
description: "Array of every video hosted on the site"
catagory: videos
---


<ul>
{%- for video in site.videos -%}


   {%- if video.youtubeID == True -%}
     {% include youtubePlayer.html ID=video.youtubeID %}
<div class="ytcontainer">
<li>
   <iframe class="ytframe" frameborder="0" allowfullscreen
   src="https://www.youtube.com/embed/{{video.youtube.ID}}"></iframe>
</li>
   </div>


<li>{{ video.title }}</li>
</li>{{ video.description }}</li>
<li><a href="{{ video.url }}">{{ video.title }}</a></li>

   {%- endif -%}

{%- endfor -%}
</ul>

<!doctype html>
<html lang="en">
<body>
  <article class="gallery" role="main">
    <section class="photos">
      {%- for photo in site.photos -%} <!-- Loop through the photos from the YAML frontmatter from an empty Jekyll post -->
      <figure>
         <img src="{{ site.image.path }}" alt="{{ site.image.path }}">
      </figure>
            <figcaption>{{ page.image-caption[forloop.index0] }}</figcaption> <!-- and the figcaption too -->
      {% endfor %}
    </section>
  </article>
</body>
</html>

y images are in a assets/images/slider directory.


<ul>
{% for photo in site.photos %}
    <li> <img src="{{ photo.image_path }}" alt="image">
    </li>
{% endfor %}
 </ul>

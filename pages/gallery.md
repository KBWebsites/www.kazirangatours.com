---
title: Gallery
permalink: /gallery/
videos:
- oibPT14SXGk
- cFkNW6Hn6yk
- Ncyl4lj7CE4
- bqHdke05Ono
pictures:
- Archeological temple ruins Assam
- Dolls at Ima market Manipur
- Elephant safari at Kaziranga National Park
- Orchids of Assam
---
<div class="row">
{% for id in page.videos %}
<article class="6u{% cycle '', '$' %} 12u$(3) work-item">
<iframe width="100%" height="300" src="//www.youtube.com/embed/{{id}}" frameborder="0" allowfullscreen></iframe>
</article>
{% endfor %}
</div>
<hr>
<div class="row">
{% for name in page.pictures %}
<article class="6u{% cycle '', '$' %} 12u$(3) work-item">
    <a href="/files/gallery/{{name}}.jpg" class="image">
        <img src="//i{% cycle '0', '1', '2' %}.wp.com/www.kazirangatours.com/files/gallery/{{name}}.jpg?h=300" alt="{{ name }}">
    </a>
    <h3>{{name}}</h3>
</article>
{% endfor %}
</div>
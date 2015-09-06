---
title: Our Guests
permalink: /our-guests/
guests:
- Antonia Joris, Canada
- Arne & Joyce, USA
- Chi, USA
- Dan, USA
- Don & Linda, USA
- Elizabeth Gibson, Canada
- Frank, Germany
- Jo, France
- Miguel Kramb, Germany
- Mr. Schoffel, Germany
- Roy & Christine, USA
---
<div id="guests">
{% for g in page.guests %}
<h3>{{ g }}</h3>
<a href="/files/testimonials/{{ g }}.jpg" title="{{ g }}"><img src="/files/testimonials/{{ g }}.jpg" alt="{{ g }}"></a>
{% endfor %}
</div>
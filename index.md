---
layout: page
---

<div class="row">
    <article class="6u 12u$(3) work-item">
        <h2>A glimpse of Northeast India</h2>
        <iframe width="100%" height="450" src="//www.youtube.com/embed/sUhZO86qyJg" frameborder="0" allowfullscreen></iframe>
    </article>
    <article class="6u$ 12u$(3) work-item">
        <h2>Visit the Anthurium Festival this year at Mizoram</h2>

        <img src="/files/anthurium1.jpg" alt="">
        
        <p>The three days colorful Anthurium festival will be held from 1st to 3rd of October this year with traditional pomp and gaiety at Lengpui mini sports complex in Mizoram, India.
        <br/>
        <a href="/upcoming-event/">Read More &rarr;</a></p>
    </article>
</div>

<hr>

<div class="row">
{% assign blocks = site.home_blocks | sort: 'index' %}
{% for block in blocks %}
<article class="6u{% cycle '', '$' %} 12u$(3) work-item">
        <a href="{{ block.img }}" class="image fit thumb">
            {% if block.img  %}
                <img src="{{ block.thumb }}" alt="{{ block.title }}">
            {% else %}
                <img src="//placehold.it/640x480&amp;text={{ block.title | cgi_escape }}" alt="">
            {% endif %}
        </a>
        <h3>{{ block.title }}</h3>
        <p>{{ block.content | strip_html | truncate: 200 }}<br/><a href="{{ block.url }}">Read More &rarr;</a></p>
</article>
{% endfor %}
</div>

<hr>

{::options parse_block_html="true" /}
<div id="about-kt">
## About Kaziranga Tours

We are tour operators promoting the seven North Eastern states of India also known as the Seven Sisters. Northeast India with its beautiful hills, valleys, lakes, rainforests, wildlife and colorful tribal people, is a tourists’ paradise. Yet due to its geographical location, this region has remained unexplored for a very long time and has come in the radar of tourism only recently.

Our company, for almost a decade now, has been a pioneer in promoting tourism in Northeast India. We specialize in organizing Wildlife, Tea, Tribal and special interest tours like Cycling, Bird watching, Culinary tours etc. We have also started community based and rural tourism for benefit of the local indigenous people.

North East India is known for its friendly people and warm hospitality. It is this tradition that our team of dedicated young tourism professionals strives to uphold at Kaziranga Tours.

We welcome you to embark on a great journey of discovery with us.
</div>
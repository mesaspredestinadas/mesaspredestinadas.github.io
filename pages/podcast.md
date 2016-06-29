---
layout: page
show_meta: false
title: "Podcasts do Mesas Predestinadas"
header:
    image_fullwidth: FundoBlog.png
permalink: "/podcast/"
---
<ul>
    {% for post in site.tags.fate-masters-podcast %} 
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>

<ul>

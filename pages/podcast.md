---
layout: page
show_meta: false
title: "Podcasts do Mesas Predestinadas"
header:
    image_fullwidth: FundoBlog.png
permalink: "/podcast/"
---

<ul>
    {% for post in site.tags.Mesas-Predestinadas %} 
    <li><a href="{{ post.url }}">{{ post.title | markdownify | remove: '<p>' | remove: '</p>' }}</a></li>
    {% endfor %}
</ul>

<ul>

{% comment %}
{% for post in site.tags.Mesas-Predestinadas %} 
+ [{{ post.title | markdownify | remove: '<p>' | remove: '</p>' }}]({{ post.url }})
{% endfor %}
{% endcomment %}

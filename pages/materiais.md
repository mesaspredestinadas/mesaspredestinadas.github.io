---
layout: page
show_meta: false
title: "Materiais relacionados"
header:
    image_fullwidth: FundoBlog.png
permalink: "/materiais/"
---

### Materiais diversos relacionados com o podcast

{% assign materiais = site.posts | where_exp:"post","post.tags contains 'materiais'" %}

<ul>
    {% for post in materiais %} 
    <li><a href="{{ post.url }}">{{ post.title | markdownify | remove: '<p>' | remove: '</p>' }}</a></li>
    {% endfor %}
</ul>

---
layout: category
title: "News"
permalink: /categories/news/
taxonomy: news
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/img/nate.jpg
---
{% for post in site.posts %}
  <li><!-- display post year here (but only once, per year) --></li>
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
{% endfor %}

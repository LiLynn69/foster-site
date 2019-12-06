---
layout: category
title: "News"
permalink: /categories/news/
taxonomy: news

header:
  overlay_image: /assets/img/ivy.jpg
---

<div class="grid__wrapper">
  {% for post in site.posts limit:4 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

---
layout: single
title: "News"
permalink: /news/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/img/nate.jpg
---
<ul>
  {% for news in site.categories.news %}
    <li>
      <a href="{{ news.url }}">{{ news.title }}</a>
      <p>{{news.meta}}</p>
    </li>
  {% endfor %}
</ul>

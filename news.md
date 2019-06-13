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
      <span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a>
      <p>{{post.meta}}</p>
    </li>
  {% endfor %}
</ul>

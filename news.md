---
layout: single
title: "Recent News"
permalink: /news/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/img/nate.jpg
---

## Recent News ##
{% for post in site.categories.news %}
 <li><span>{{ post.date | date_to_string }}</span> &nbsp; <a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

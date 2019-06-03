---
layout: single
title: "News"
permalink: /news/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/img/nate.jpg
---

{% for post in site.categories.news %}
 <li><span>{{ news.date | date_to_string }}</span> &nbsp; <a href="{{ news.url }}">{{ news.title }}</a></li>
{% endfor %}

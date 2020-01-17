---
title: "Events by Category"
layout: categories
permalink: /categories/
---
{% for category in site.categories %}
   {{ category | first | strip_html }}
{% endfor %}

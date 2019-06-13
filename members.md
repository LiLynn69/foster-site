---
title: Nates Group Members
layout: collection
permalink: /members/
collection: members
entries_layout: grid
classes: wide
sort_by: title
header:
  overlay_color: "#050505"
  overlay_filter: "0.2"
  overlay_image: /assets/img/nate.jpg
---
  
{% for member in site.smembers %}
  <h2>{{ member.name }} - {{ member.position }}</h2>
  <p>{{ member.content | markdownify }}</p>
{% endfor %}

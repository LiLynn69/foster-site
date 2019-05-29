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
{% for members in site.members %}
  <h2>{{ members.name }} - {{ members.position }}</h2>
  <p>{{ members.content | markdownify }}</p>
{% endfor %}





  

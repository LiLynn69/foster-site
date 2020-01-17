---
layout: events
title: "Events"
permalink: /events/
collection: events
taxonomy: 
 - Retreats
 - Seminars
 - Workshops
classes:
 - landing
 - wide
header:
  overlay_image: /assets/img/ivy.jpg
---
{%a assign col  = site.events %}
{% for cat in col %}
   {{ col.events }}
{% endfor %}

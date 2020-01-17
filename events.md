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
{{% for category in site.events %}
   {{ category | first | strip_html }}
{% endfor %}

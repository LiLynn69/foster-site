---
layout: archive
title: "Recent News"
permalink: /news/
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/img/nate.jpg
---
## Check out our recent news!

{% for post in site.pages %}
  {% include archive-single.html %}
{% endfor %}

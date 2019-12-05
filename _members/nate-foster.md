---
title: "Nate Foster"
layout: member
excerpt: (Co-Director) Cornell
order_number: 10

header:
  image: /assets/img/nate.jpg 
  teaser: /assets/img/nate.jpg
---
{% assign ordered_pages = site.pages | sort:"order_number" %}
{% for page in ordered_pages %}
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>
{% endfor %}

![left-aligned-image][Nate Foster](../../assets/img/nate.jpg){: .align-left}{: .img-responsive}{: .img-circle} 
## Cornell
something more here? Add social icons?

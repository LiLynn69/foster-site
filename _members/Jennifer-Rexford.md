---
title: "Jennifer Rexford"
layout: member
excerpt: "(Co-Director) Princeton"
order_number: 20
header:
  image: /assets/img/jen.jpg
  teaser: /assets/img/jen.jpg
---
{% assign ordered_pages = site.pages | sort:"order_number" %}
{% for page in ordered_pages %}
  <a href="{{ page.url | relative_url }}">{{ page.title }}</a>


![left-aligned-image](../../assets/img/jen.jpg){: .align-left}{: .img-circle}{: .img-responsive} 
## Jennifer Rexford

fdasjkl jkafs jk;lf ajkfs djlksdf jkl jfadslk jafsdlk jlsadf; jlkafsd jlkfsd ljkafs klafsdj l;afsdkj ladfksj afdslkj fasdlk;j asdflkj afdslkj fdsalk jlafsdkj l;kdfsaj lkafsdj ladfksjalsdfkjadflsjk

{% endfor %}

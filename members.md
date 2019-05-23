---
title: Members
layout: members
permalink: /members/
collection: members
entries_layout: grid
classes: wide, members
sidebar:
  nav: "members"
header:
  overlay_color: "#050505"
  overlay_filter: "0.2"
  overlay_image: /assets/img/nate.jpg
---

{% for members in site.members %}
	<div class="members">
		<h2><a href="{{ members.url }}">{{ members.title }}</a></h2>
	</div>
{% endfor %}


  

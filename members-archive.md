---
title: Members
layout: collection
permalink: /members/
collection: members
entries_layout: grid
classes: wide
sidebar:
  nav: "members"
header:
  overlay_color: "#050505"
  overlay_filter: "0.2"
  overlay_image: /assets/img/nate.jpg
---

## Meet Nates' Awesome Group 

{% for members in site.members %}
  <div class="members">
    <h2><img src="{{ members.image_path }}" alt="{{ members.alt }}" />{{ members.title }}</h2>
    {{ members.content }}
  </div>
{% endfor %}
  

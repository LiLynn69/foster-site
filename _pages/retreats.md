---
title: Retreats
layout: category
permalink: /categories/retreats/
collection: events
taxonomy: Retreats
sidebar:
  nav: "events"
---

{% assign category = page.title|downcase %}

    {% for post in site.events %}
    {% if post.categories contains {{category}}  %}
    <li>{{ post.title }}</li>
    {% endif %}
    {% endfor %}

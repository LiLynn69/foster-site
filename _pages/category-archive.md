---
title: "Events by Category"
layout: categories
permalink: /categories/
---

{% assign categories_array = "" | split:"|" %}

{% for post in site.events %} {% for category in post.categories %} {% assign categories_array = categories_array | push: category | uniq %} {% endfor %} {% endfor %}

{% for category in categories_array %} {{ category }} {% endfor %}

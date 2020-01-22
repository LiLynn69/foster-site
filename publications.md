---
layout: collection
title: "Publications"
permalink: /publications/
classes:
 - landing

header:
  overlay_image: /assets/img/ivy.jpg
---
<div class="container">
    
{% assign journals = site.data.publications | where:'type','journal' | sort:'date' | reverse %}
{% assign conferences = site.data.publications | where:'type','conference' | sort:'date' | reverse %}
{% assign workshops = site.data.publications | where:'type','workshop' | sort:'date' | reverse %}
{% assign posters = site.data.publications | where:'type','poster' | sort:'date' | reverse %}
{% assign dissertations = site.data.publications | where:'type','dissertation' | sort:'date' | reverse %}

<h2>Journals</h2>
<ul>        
{% for paper in journals %}
{% include publication.html %}
{% endfor %}
</ul> 

<h2>Conferences</h2>
<ul>        
{% for paper in conferences %}
{% include publication.html %}
{% endfor %}
</ul> 

<h2>Workshops</h2>
<ul>        
{% for paper in workshops %}
{% include publication.html %}
{% endfor %}
</ul> 

<h2>Posters</h2>
<ul>        
{% for paper in posters %}
{% include publication.html %}
{% endfor %}
</ul> 
    
<h2>Dissertations</h2>
<ul>
{% for paper in dissertations %}
{% include publication-dissertation.html %}
{% endfor %}
</ul>
</div>

---
layout: page
title: Archive
permalink: /archive/
feature_image: feature-book
---

<ul>
{% for post in site.posts %}	
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    <small><strong>{{ post.date | date: "%B %e, %Y" }}</strong></small>			
{% endfor %}	
</ul>

<!--
<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>, <small>{{ post.date | date: "%B %e, %Y" }}</small>	
    </li>
  {% endfor %}
</ul>
-->

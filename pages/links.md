---
layout: mypost
title: Links
---

Welcome to other pages of mine


<ul>
  {% for link in site.links %}
  <li>
    <p><a href="{{ link.url }}" title="{{ link.desc }}" target="_blank" >{{ link.title }}</a></p>
  </li>
  {% endfor %}
</ul>

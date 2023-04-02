---
title: Eventos
layout: blog-index
permalink: /eventes/
---
# Eventos
<ul>
  {% for event in site.events %}
    <li>
      <a href="{{ event.url }}">{{ event.title }}</a>
    </li>
  {% endfor %}
</ul>
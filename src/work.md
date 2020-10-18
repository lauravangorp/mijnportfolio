---
title: ''
layout: 'layouts/page.html'
---

<div class="works">
{% for item in collections.featuredWork %}
  <a href="{{ item.url }}">
    <img src="{{ item.data.image }}" alt="{{ item.data.summary }}"/>
  </a>
{% endfor %}
</div>

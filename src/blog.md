---
title: Blog
layout: 'layouts/page.html'
---

Here you can find interesting blogs I have found on the internet about the artists that inspire me.

### Recent posts

<ul class="blog">
{%- for post in collections.post | reverse -%}
  <li>
    <a href="{{ post.url | url }}">
      {{ post.data.title }}{{ item.data.image }}
    </a>
 </li>
{%- endfor -%}
</ul>

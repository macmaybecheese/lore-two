---
title: The Ones
---

Made a shitty fockin website to host my half-baked worldbuilding

i suggest going from the bottom up 

<ul>
  {% for post in site.posts reversed %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

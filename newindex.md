---
title: The Ones
---

# The Ones

Made a shitty fockin website to host my half-baked worldbuilding

## Articles

<ul style="list-style-type: none;">
  {% for post in site.posts reversed %}
    <li>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
    </li>
  {% endfor %}
</ul>

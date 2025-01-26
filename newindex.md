---
title: The Ones
---

# The Ones

Made a shitty fockin website to host my half-baked worldbuilding

## Articles

<ul style="list-style-type: none;">
  {% for post in site.posts reversed %}
    <li>
      <p style="font-size: 14px; color: #828282;">{{ post.date }}</p>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <br>
    </li>
  {% endfor %}
</ul>

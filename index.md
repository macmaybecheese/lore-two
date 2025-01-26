---
title: The Ones
---

# The Ones

Made a shitty fockin website to host my half-baked worldbuilding

## Magic
{% for magic in site.tags %}
<ul style="list-style-type: none;">
  {% for post in magic[1] reversed %}
    <li>
      <p style="font-size: 14px; color: #828282;">{{ post.date | date_to_string }}</p>
      <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
      <br>
    </li>
  {% endfor %}
</ul>
{% endfor %}

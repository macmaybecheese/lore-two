---
title: Livestream Lore™
---

# Livestream Lore™

Made a shitty fockin website to host my half-baked worldbuilding which I guess I will now livestream before my friends

## Blog Posts Cus' This Is Fucking Jekyll
{% for magic in site.tags %}
  {% assign date_format = site.minima.date_format | default: "%b %-d, %Y" %}
  <ul style="list-style-type: none;">
    {% for post in magic[1] reversed %}
      <li>
        <p style="font-size: 14px; color: #828282;">{{ post.date | date: date_format }}</p>
        <h3><a href="{{ post.url |  relative_url }}">{{ post.title }}</a></h3>
        <br>
      </li>
    {% endfor %}
  </ul>
{% endfor %}




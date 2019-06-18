---
layout: page
title: "Photo Gallery of various workshops"
---

{% assign year_group = site.data.galleries | group_by: "year" %}
{% for year in year_group %}
  {{ year.name }}
  {% assign galleries = year.items %}
  {% for gallery in galleries %}
  - [{{ gallery.description }}](/galleries/{{ gallery.id }})
  {% endfor %}
{% endfor %}


---

See [Documents](/documents), [Workshops](/workshops) or [Services](/services)

---
layout: page
title: "Photo Gallery of various workshops"
---

2016
{% for gallery in site.data.galleries %}
{% if gallery.year == 2016 %}
  {{ gallery.date }}
  - [{{ gallery.description }}](/galleries/{{ gallery.id }})
{% endif %}
{% endfor %}

2015
{% for gallery in site.data.galleries %}
{% if gallery.year == 2015 %}
  {{ gallery.date }}
  - [{{ gallery.description }}](/galleries/{{ gallery.id }})
{% endif %}
{% endfor %}

2014
{% for gallery in site.data.galleries %}
{% if gallery.year == 2014 %}
  {{ gallery.date }}
  - [{{ gallery.description }}](/galleries/{{ gallery.id }})
{% endif %}
{% endfor %}

---

See [Documents](/documents), [Workshops](/workshops) or [Services](/services)

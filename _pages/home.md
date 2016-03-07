---
layout: archive
permalink: /
excerpt: "A minimal Jekyll theme for your blog by designer Michael Rose."
header:
  image: unsplash-image-7.jpg
  caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
---

{% include base_path %}

### Recent Posts

{% for post in site.posts limit:5 %}
  {% include archive-list-single %}
{% endfor %}
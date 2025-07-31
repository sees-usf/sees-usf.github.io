---
layout: default
---
# Gallery
Pictures of past events in SEES Lab.
{% for image in site.data.gallery.photos %}
{% include image_frame.html src=image %}
{% endfor %}
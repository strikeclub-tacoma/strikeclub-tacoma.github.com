---
layout: page
title: "Frames"
permalink: /frames/
---

{% for page in site.pages %}
  {% if page.layout == "frame" %}
  <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">Frame {{ page.frame_number }}, on {{ page.event_date }} </a>
  {% endif %}
{% endfor %}
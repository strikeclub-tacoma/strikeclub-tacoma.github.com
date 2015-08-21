---
layout: page
title: "Frames"
permalink: /frames/
---

{% for page in site.pages %}
  {% if page.layout == "frame" %}
  <p>
  <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">Frame {{ page.frame_number }}, -- Organized By: {{ page.organizer }}<br />
  Date: {{ page.event_date }}<br /></a>
  </p>
  {% endif %}
{% endfor %}

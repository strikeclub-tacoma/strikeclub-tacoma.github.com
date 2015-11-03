---
layout: page
title: "Ideas"
permalink: /ideas/
---

The following are ideas for strike club events.  Some ideas are completely fleshed out, while others are just the result of a brain storming session.  Use them individually if you wish, or put two or more together to build an unforgettable Strike Club experience.

{% for page in site.ideas %}
  <p>
  <a class="page-link" href="{{ page.url | prepend: site.baseurl }}">{{ page.title }}</a> -- 
  {{ page.summary | downcase }}
  </p>
{% endfor %}

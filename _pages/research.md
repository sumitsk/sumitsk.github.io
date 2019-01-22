---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<!-- add projects here -->
{% include base_path %}

{% for post in site.research reversed %}
  {% include archive-single.html %}
{% endfor %}

<!-- <div class="grid__wrapper">
{% for post in site.research%}
  {% include archive-single.html %}
{% endfor %}
</div> -->

---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

<!-- add projects here -->
{% include base_path %}

<!-- {% for post in site.projects reversed %} -->
{% for post in site.portfolio %}
  {% include archive-single.html %}
{% endfor %}

<!-- <div class="grid__wrapper">
{% for post in site.projects%}
  {% include archive-single.html %}
{% endfor %}
</div> -->

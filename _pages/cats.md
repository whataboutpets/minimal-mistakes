---
layout: archive
title: "Cats"
permalink: /cats/
---

<div class="grid__wrapper">
  {% for post in site.categories.Cats %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

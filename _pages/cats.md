---
layout: archive
title: What About Cats2?
permalink: /cats/
author_profile: false
---

<div class="grid__wrapper">
  {% for post in site.categories.cats %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

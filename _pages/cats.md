---
layout: archive
title: "What About Cats?"
permalink: /cats/
author_profile: false
---

<div class="grid__wrapper">
  {% for post in site.categories.Cats %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

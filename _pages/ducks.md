---
layout: archive
title: "What About Ducks?"
permalink: /ducks/
author_profile: false
---

<div class="grid__wrapper">
  {% for post in site.categories.Ducks %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>

---
layout: archive-page
title: "Ducks"
permalink: /ducks/
no_title: true
---

<section class="page__content" itemprop="text" markdown="1">
  <h2 class="cf align-center h2-margin-top">Latest Duck Tips and Advice</h2>
</section>

<div class="grid__wrapper">
  {% for post in site.categories.Ducks %}
    {% if post.tags contains 'Advice' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<section class="page__content" itemprop="text" markdown="1">
  <h2 class="cf align-center">Feeding Guides and Tips</h2>
</section>

<div class="grid__wrapper">
  {% for post in site.categories.Ducks %}
    {% if post.tags contains 'Feed' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

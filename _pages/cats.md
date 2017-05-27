---
layout: archive-page
title: "Cats"
permalink: /cats/
no_title: true
---

<section class="page__content" itemprop="text" markdown="1">
  <h2 class="cf align-center h2-margin-top">Latest Cat Tips and Advice</h2>
</section>

<div class="grid__wrapper">
  {% for post in site.categories.Cats %}
    {% if post.tags contains 'Advice' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

<section class="page__content" itemprop="text" markdown="1">
  <h2 class="cf align-center">Buying Guides and Reviews</h2>
</section>

<div class="grid__wrapper">
  {% for post in site.categories.Cats %}
    {% if post.tags contains 'Review' %}
      {% include archive-single.html type="grid" %}
    {% endif %}
  {% endfor %}
</div>

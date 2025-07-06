---
layout: archive
title: "Photos"
permalink: /photos/
author_profile: true
---

{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.photos reversed %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
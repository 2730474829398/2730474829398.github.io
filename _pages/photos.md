---
layout: archive
title: "Photos"
permalink: /photos/
author_profile: true
---

{% raw %}{% include base_path %}

<div class="grid__wrapper">
  {% for post in site.photos reversed %}
    {% include archive-photo-grid.html %}
  {% endfor %}
</div>{% endraw %}
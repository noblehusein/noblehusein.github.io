---
layout: archive
title: "Professional Experience"
permalink: /experience/
author_profile: true
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% if post.type == "Professional Experience" %}
    {% include archive-single.html %}
  {% endif %}
{% endfor %} 
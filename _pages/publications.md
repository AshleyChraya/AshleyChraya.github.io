---
layout: archive
title: "Now"
permalink: /now/
author_profile: true
---

{% include base_path %}

{% for post in site.notes reversed %}
  {% include archive-single.html %}
{% endfor %}

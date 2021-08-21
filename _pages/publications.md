---
layout: archive
title: "Now"
permalink: /now/
author_profile: false
---

{% include base_path %}

{% for post in site.now reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "problems"
permalink: /problems/
author_profile: false
---

{% include base_path %}

{% for post in site.teaching reversed %}
  {% include archive-single.html %}
{% endfor %}

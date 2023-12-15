---
layout: archive-notitle
title: "Projects"
permalink: /projects/
author_profile: true
image_sliders_load_all: true
---

{% include base_path %}

{% for post in site.projects %}
   {% include archive-single.html %}
{% endfor %}

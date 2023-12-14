---
layout: archive
title: "Fieldworks"
permalink: /fieldworks/
author_profile: true
carousels:
  - images:
  - images:
    - image: /images/Poltron-01.png
    - image: /images/Poltron-01-dark.png  
  - images:
    - image: /images/weevil-shutterstock_749333035w.jpeg
    - image: /images/Poltron-01.png
---

{% include base_path %}


{% for post in site.fieldworks reversed %}
  {% include archive-single.html %}
  {% capture project_number %}
  {{ post.number}}
  {% endcapture %}
  {% include carousel.html height="50" unit="%" duration="2" number=project_number %}
{% endfor %}

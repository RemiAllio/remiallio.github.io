---
layout: archive
title: "Fieldworks"
permalink: /fieldworks/
author_profile: true
carousels:
  - images:
    - image: /images/RSA-0.JPG
    - image: /images/RSA-1.JPG
    - image: /images/RSA-2.JPG
    - image: /images/RSA-3.JPG
    - image: /images/RSA-4.JPG
    - image: /images/RSA-5.JPG
    - image: /images/RSA-6.JPG
    - image: /images/RSA-7.JPG
    - image: /images/RSA-8.JPG
  - images:
    - image: /images/Gabon-0.JPG
    - image: /images/Gabon-1.JPG
    - image: /images/Gabon-2.JPG
    - image: /images/Gabon-3.JPG
    - image: /images/Gabon-4.JPG
    - image: /images/Gabon-5.JPG
    - image: /images/Gabon-6.JPG
---

{% include base_path %}


{% for post in site.fieldworks reversed %}
  {% include archive-single.html %}
  {% capture project_number %}
  {{ post.number}}
  {% endcapture %}
  {% include carousel.html height="60" unit="%" duration="3" number=project_number %}
{% endfor %}

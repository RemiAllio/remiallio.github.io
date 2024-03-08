---
layout: archive-notitle
title: "Fieldwork"
permalink: /fieldwork/
author_profile: true
carousels:
  - images:
    - image: /images/Rémi-Allio-Paysage_AFSUD_01.jpg
    - image: /images/Rémi-Allio-Entiminae_AFSUD_01.jpg
    - image: /images/Rémi-Allio-Entiminae_AFSUD_02.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_02.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_03.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_04.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_05.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_06.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_07.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_08.jpg
    - image: /images/Rémi-Allio-Paysage_AFSUD_09.jpg
  - images:
    - image: /images/Rémi-Allio-Gabon-0.JPG
    - image: /images/Rémi-Allio-Endaeus_Gabon_SiteWeb_31-10-23_0N4A4172.jpg
    - image: /images/Rémi-Allio-Gabon-1.JPG
    - image: /images/Rémi-Allio-Gabon-2.JPG
    - image: /images/Rémi-Allio-Gabon-3.JPG
    - image: /images/Rémi-Allio-Endaeus_Gabon_SiteWeb_31-10-23_0N4A4199.jpg
    - image: /images/Rémi-Allio-Gabon-4.JPG
    - image: /images/Rémi-Allio-Gabon-5.JPG
    - image: /images/Rémi-Allio-Gabon-6.JPG
---

{% include base_path %}


{% for post in site.fieldwork reversed %}
  {% include archive-single.html %}
  {% capture project_number %}
  {{ post.number}}
  {% endcapture %}
  {% include carousel.html height="60" unit="%" duration="160" number=project_number %}
{% endfor %}

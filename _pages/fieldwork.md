---
layout: archive-notitle
title: "Fieldwork"
permalink: /fieldwork/
author_profile: true
carousels:
  - images:
    - image: /images/Paysage_AFSUD_01.JPG
    - image: /images/Entiminae_AFSUD_01.jpg
    - image: /images/Entiminae_AFSUD_02.jpg
    - image: /images/Paysage_AFSUD_02.JPG
    - image: /images/Paysage_AFSUD_03.JPG
    - image: /images/Paysage_AFSUD_04.JPG
    - image: /images/Paysage_AFSUD_05.JPG
    - image: /images/Paysage_AFSUD_06.JPG
    - image: /images/Paysage_AFSUD_07.JPG
    - image: /images/Paysage_AFSUD_08.JPG
    - image: /images/Paysage_AFSUD_09.JPG
  - images:
    - image: /images/Gabon-0.JPG
    - image: /images/Endaeus_Gabon_SiteWeb_31-10-23_0N4A4172.jpg
    - image: /images/Gabon-1.JPG
    - image: /images/Gabon-2.JPG
    - image: /images/Gabon-3.JPG
    - image: /images/Endaeus_Gabon_SiteWeb_31-10-23_0N4A4199.jpg
    - image: /images/Gabon-4.JPG
    - image: /images/Gabon-5.JPG
    - image: /images/Gabon-6.JPG
---

{% include base_path %}


{% for post in site.fieldwork reversed %}
  {% include archive-single.html %}
  {% capture project_number %}
  {{ post.number}}
  {% endcapture %}
  {% include carousel.html height="60" unit="%" duration="160" number=project_number %}
{% endfor %}

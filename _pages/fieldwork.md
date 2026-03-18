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
    - image: /images/Rémi-Allio-Gabon-0.jpg
    - image: /images/Rémi-Allio-Endaeus_Gabon_SiteWeb_31-10-23_0N4A4172.jpg
    - image: /images/Rémi-Allio-Gabon-1.jpg
    - image: /images/Rémi-Allio-Gabon-2.jpg
    - image: /images/Rémi-Allio-Gabon-3.jpg
    - image: /images/Rémi-Allio-Endaeus_Gabon_SiteWeb_31-10-23_0N4A4199.jpg
    - image: /images/Rémi-Allio-Gabon-4.jpg
    - image: /images/Rémi-Allio-Gabon-5.jpg
    - image: /images/Rémi-Allio-Gabon-6.jpg
  - images:
    - image: /images/Rémi-Allio-CostaRica-0.jpg
    - image: /images/Rémi-Allio-CostaRica-1.jpg
    - image: /images/Rémi-Allio-CostaRica-2.jpg
    - image: /images/Rémi-Allio-CostaRica-3.jpg
    - image: /images/Rémi-Allio-CostaRica-4.jpg
    - image: /images/Rémi-Allio-CostaRica-5.jpg
    - image: /images/Rémi-Allio-CostaRica-6.jpg
    - image: /images/Rémi-Allio-CostaRica-7.jpg
    - image: /images/Rémi-Allio-CostaRica-8.jpg
    - image: /images/Rémi-Allio-CostaRica-9.jpg
    - image: /images/Rémi-Allio-CostaRica-10.jpg
    - image: /images/Rémi-Allio-CostaRica-11.jpg
  - images:
    - image: /images/Rémi-Allio-Guyane2025-01.jpg
    - image: /images/Rémi-Allio-Guyane2025-02.jpg
    - image: /images/Rémi-Allio-Guyane2025-03.jpg
    - image: /images/Rémi-Allio-Guyane2025-04.jpg
    - image: /images/Rémi-Allio-Guyane2025-05.jpg
    - image: /images/Rémi-Allio-Guyane2025-06.jpg
    - image: /images/Rémi-Allio-Guyane2025-07.jpg
    - image: /images/Rémi-Allio-Guyane2025-08.jpg
    - image: /images/Rémi-Allio-Guyane2025-09.jpg
    - image: /images/Rémi-Allio-Guyane2025-10.jpg
    - image: /images/Rémi-Allio-Guyane2025-11.jpg
    - image: /images/Rémi-Allio-Guyane2025-12.jpg
    - image: /images/Rémi-Allio-Guyane2025-13.jpg
    - image: /images/Rémi-Allio-Guyane2025-14.jpg
    - image: /images/Rémi-Allio-Guyane2025-15.jpg
    - image: /images/Rémi-Allio-Guyane2025-16.jpg
    - image: /images/Rémi-Allio-Guyane2025-17.jpg
    - image: /images/Rémi-Allio-Guyane2025-18.jpg
    - image: /images/Rémi-Allio-Guyane2025-19.jpg
    - image: /images/Rémi-Allio-Guyane2025-20.jpg
    - image: /images/Rémi-Allio-Guyane2025-21.jpg
---

{% include base_path %}


{% for post in site.fieldwork reversed %}
  {% include archive-single.html %}
  {% capture project_number %}
  {{ post.number}}
  {% endcapture %}
  {% include carousel.html height="60" unit="%" duration="160" number=project_number %}
{% endfor %}

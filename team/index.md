---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

The Illinois Laboratory for Animal Machine-learning and Bioinformatics is an interdisciplinary research laboratory that focuses on computational methods development in single cell and spatial technologies and the research of immunology and genomics in animals. 

{% include section.html %}

{% include list.html data="members" component="portrait" filters="group: ^current" %}
<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %} -->

# Lab Alumni

{% include list.html data="members" component="portrait" filters="group: former" %}

{% include section.html background="images/background.jpg" dark=true %}



{% include section.html %}

{% capture content %}

{% include figure.html image="images/Gallery/labgroup1crop.jpg" %}
{% include figure.html image="images/Gallery/AlexisImmunology24(2).jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

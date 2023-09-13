---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html %}
# {% include icon.html icon="fa-solid fa-bullhorn" %}Join us!

The Li Lab has multiple open positions for postdoctoral fellows, research specialists, and bioinformaticians.

The Li Lab is also recruiting several graduate students at the University of Pennsylvania! If interested in rotating in our lab, please email Dr. Li with a brief statement of your interest and CV at qinl@stanford.edu.

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->

---
title: Team
nav:
  order: 2
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

## Principal Investigator
{% include list.html data="members" component="portrait" filters="role: pi" %}

----
## Phd
{% include list.html data="members" component="portrait" filters="role: phd" %}

----
## Master
{% include list.html data="members" component="portrait" filters="role: undergrad3" %}
{% include list.html data="members" component="portrait" filters="role: undergrad2" %}
{% include list.html data="members" component="portrait" filters="role: undergrad1" %}
<!-- {% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %} -->
----
## Graduate
{% include list.html data="members" component="portrait" filters="role: graduate" %}

{% include section.html %}
# {% include icon.html icon="fa-solid fa-bullhorn" %}Join us!

The Xu Lab has open positions at all levels.

We also welcomes graduate/undergraduate students interested in AI for health! If interested, please email Dr. Xu with a brief statement of your interest and CV at mxu[at]dlut.edu.cn.

<!-- {% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %} -->

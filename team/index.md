---
title: People
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}People
{% include section.html %}

{% include list.html data="members" component="portrait" filter="group != 'alumni'" %}

{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni
{% include list.html data="members" component="portrait" filter="group == 'alumni'" %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: PhD" %}


{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Master's

{% include list.html data="members" component="portrait" filters="role: Master's student" %}

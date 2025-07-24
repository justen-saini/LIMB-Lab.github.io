---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Principal Investigator

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role: Pi" %}


{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}PhD students

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role: PhD student" %}


{% include section.html background="images/background.jpg" dark=true %}
{% include section.html %}

# {% include icon.html icon="fa-solid fa-graduation-cap" %}Masters students

{% include list.html data="members" component="portrait" filter="role: Master's student" %}

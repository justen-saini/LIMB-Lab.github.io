---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %} Team

## Principal Investigator
{% include list.html data="members" component="portrait" filter="role == 'Principal Investigator'" %}

## Research Assistant
{% include list.html data="members" component="portrait" filter="role == 'Research Assistant'" %}

## PhD Students
{% include list.html data="members" component="portrait" filter="role == 'PhD Student'" %}

## Masters Students
{% include list.html data="members" component="portrait" filter="role == 'Masters Student'" %}

## Summer Students
{% include list.html data="members" component="portrait" filter="role == 'Summer Student'" %}

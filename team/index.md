---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team
Learn more about the team by clicking on their picture!

{% include section.html %}

## Principal Investigators
{% include list.html data="members" component="portrait" filter="role == 'principal-investigator'" %}

## Postdocs
{% include list.html data="members" component="portrait" filter="role == 'postdoc'" %}

## Students
{% include list.html data="members" component="portrait" filter="role == 'phd'" %}

## Staff
{% include list.html data="members" component="portrait" filter="role == 'staff'" %}

## Collaborators
{% include list.html data="members" component="portrait" filter="role == 'collaborator'" %}

## Alumni
{% include list.html data="members" component="portrait" filter="role == 'Alumni'" %}
{% include section.html background="images/painting2024_5.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/painting2024_5.jpg" %}
{% include figure.html image="images/MickleLab_Cairibu2026.jpg" %}
{% include figure.html image="images/Hok_lab_action.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}

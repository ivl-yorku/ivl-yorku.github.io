---
title: Team
redirect_from:
  - /lab-members
  - /alums
  - /mascots
  - /staff
  - /trainees
---

# <i class="fas fa-users"></i> Team Members of Intelligent Visualization Lab


## Principal Investigator 
{% capture html %}
{% include team-list.html role="pi" group="current" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Current Members

Our lab is a team focused on improving the reach, accuracy, and speed of information visualization and accessibility. 
We are a varied and friendly bunch. If you're interested in 
the work we're doing, please reach out!
{:.center}

{% capture html %}
{% include team-list.html role="postdoc" group="current" %}
{% include team-list.html role="phd" group="current" %}
{% include team-list.html role="msc" group="current" %}
{% include team-list.html role="undergrad" group="current" %}
{% include team-list.html role="programmer" group="current" %}
{% include team-list.html role="mascot" group="current" %}
{% endcapture %}

{% include centerer.html html=html %}

<!-- section break -->

## Alumni

We are incredibly proud of all the IVL alumni who have passed through the lab, for whatever period of time they were with us. Below
is a list of lab alumni (if you feel you're missing from the list and would like to be added, please e-mail us):
{:.center}

{% capture html %}
{% include team-list.html role="pi" group="alum" mini="true" %}
{% include team-list.html role="phd_g" group="alum" mini="true" %}
{% include team-list.html role="msc" group="alum" mini="true" %}
{% include team-list.html role="undergrad" group="alum" mini="true" %}
{% endcapture %}

{% include centerer.html html=html %}

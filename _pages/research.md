---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
header:
  og_image: "research/ecdf.png"
---

My academic research falls into three main areas: 
(1) understanding citizens' preferences for and satisfaction with election outcomes,
(2) examining electoral accountability specifically during election campaigns, 
and (3) investigating how citizens perceive electoral institutions in both established democracies and more fragile settings.

I am currently leading one third-party founded project. The project is an ERC Starting Grant called DeVOTE (2021-2025) that aims to develop and apply a new theoretical  and methodological approach to study what ‘voting’ means for ordinary citizens in established democracies and electoral autocracies. Recently I have completed a project funded by the Austrian Science Fund (2018-2023) in which I studied how citizens respond to the compromises parties need to make to form governments and pass legislation in parliament. 

<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

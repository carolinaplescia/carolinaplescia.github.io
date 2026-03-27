---
layout: archive
title: ""
permalink: /devote/
author_profile: true
header:
  og_image: "devote/ecdf.png"
---

DeVOTE is a research project funded by the European Research Council (ERC) Starting Grant from January 2021 to December 2026. The project is hosted by the [Department of Government](https://staatswissenschaft.univie.ac.at/en/) at the University of Vienna.

The project develops and applies a new interdisciplinary theoretical and methodological approach to study what ‘voting’ means for ordinary citizens. 

‘Meaning’, in this project, refers to both the importance of voting for citizens as well as what is meant by voting for citizens, which may encompass citizen definitions or understandings of voting and/or the motivations they have for voting or not.

The overall objective of the project is to gather citizens' views via a novel methodological approach, based on the citizen-science website and inductive reasoning, combined with panel data, vignette experiments and topic modelling. A short introductory video is available via <a href="https://www.youtube.com/watch?v=9GZn_rZgK6E">this link</a>.

Research questions:

(1) Is there a meaning of ‘voting’ for ordinary citizens? If so, what is the significance of voting for ordinary citizens? And how should we study it? (<i>Work Package 1</i>)

(2) Does the meaning of voting for ordinary citizens vary in systematic ways? What are the individual- and country-level correlates for the meanings of voting? (<i>Work Package 2</i>)

(3) Does the meaning of voting for ordinary citizens change during election times? For whom, under what conditions and which meanings are activated and/or modified by election campaigns? (<i>Work Package 3</i>)

(4) What are the attitudinal and behavioural consequences of citizen meanings? Do citizen meanings have consequences for citizen preferences, attitudes and political behaviours? (<i>Work Package 4</i>)
<nbsp>

{% include base_path %}

{% assign ordered_pages = site.research | sort:"order_number" %}

{% for post in ordered_pages %}
  {% include archive-single.html type="grid" %}
{% endfor %}

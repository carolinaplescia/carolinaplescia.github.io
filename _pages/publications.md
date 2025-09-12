---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

The following list includes peer-reviewed articles and books only. For a complete list of publications including book chapters, and research data, please refer to my CV. Feel free to contact me with any questions or to request access to replication materials when not already provided.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


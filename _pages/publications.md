---
layout: archive
title: "Research and Work in Progress"
permalink: /publications/
author_profile: true
---

Please find below the different research projects I have worked on. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

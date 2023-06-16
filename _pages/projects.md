---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---
Source code for some of the projects are not made public because of academic integrity, please connect with me if you want to learn more about those projects.

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}

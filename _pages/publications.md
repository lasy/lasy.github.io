---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---


The most up-to-date list of publications can be found on <u><a href="https://scholar.google.com/citations?hl=en&user=Qi_sA3AAAAAJ">my Google Scholar profile</a>.</u>

The list below provides `.pdf` copies of most publications.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

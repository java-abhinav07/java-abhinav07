---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Find my latest work here, for an exhaustive list kindly navigate to find the CV instead. 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{https://scholar.google.com/citations?user=g--_R9wAAAAJ&hl=en}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

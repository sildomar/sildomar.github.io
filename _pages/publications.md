---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

You can find his list of publications on <u><a href="ttps://scholar.google.com/citations?user=qnuEvzEAAAAJ" target="_blank">his Google Scholar profile</a>.</u>

{% if author.googlescholar %}
  You can find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

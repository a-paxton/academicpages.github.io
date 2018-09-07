---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
redirect_from:
  - /resume
---

Mentees’ names underlined. Asterisk indicates dual first-author position.
**Articles provided for personal use only.**

You can also find my articles on <u><a href="https://scholar.google.com/citations?user=YRWfuEIAAAAJ&hl=en&oi=sra">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}

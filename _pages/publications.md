---
layout: archive
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

You can also find a complete list of my publications on my [Google Scholar](https://scholar.google.ca/citations?user=PiIspqkAAAAJ&hl=en&oi=ao) profile.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}





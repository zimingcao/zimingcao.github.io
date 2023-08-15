---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Find My Publications on [My Google Scholar](https://scholar.google.com/citations?user=T6ZNwtAAAAAJ&hl=en&oi=ao) 

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

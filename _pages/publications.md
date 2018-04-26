---
title: "Selected Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

The following publications report on studies I was directly involved in, analyzed data for, or contributed text, figures, and data products to:

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true
---
<!-- Click the titles for more details! -->

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

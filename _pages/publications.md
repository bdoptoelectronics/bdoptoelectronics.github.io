---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
Papers on which I am a lead author are distinguished in the list below by the inclusion of their full abstract.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

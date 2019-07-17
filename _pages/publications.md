---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

Nothing lately. Older work is below, however. 


{% for post in site.publications %}
  {% include archive-single.html %}
{% endfor %}

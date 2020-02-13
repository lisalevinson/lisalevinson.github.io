---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

Click through for full abstracts, PDFs, and other related materials.

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

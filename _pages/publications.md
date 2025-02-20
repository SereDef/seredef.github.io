---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

I try to keep this overview up to date, but you can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

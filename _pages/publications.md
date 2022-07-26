---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<u><a href="{{author.googlescholar}}">Google Scholar will be the most up-to-date.</a></u>

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

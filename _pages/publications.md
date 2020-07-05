---
title: Publications
permalink: "/publications/"
layout: archive
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

You can also find my articles on <a href="http://lattes.cnpq.br/0442142220296336">my Lattes CV</a>.

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

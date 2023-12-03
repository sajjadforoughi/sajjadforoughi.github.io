---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
<embed src="{{ site.baseurl }}/files/publications.pdf" width="600" height="700" type='application/pdf'>
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


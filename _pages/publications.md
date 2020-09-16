---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---
A full list of Dr. Edward Minchin's publications and related work can be accessed with the [following link](http://ngbrianyc.github.io/files/PUBLICATIONS.pdf):
<br>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

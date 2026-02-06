---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<h2 class="archive__subtitle">Peer-reviewed Papers</h2> 
{% if author.googlescholar %}
  You can also find my papers on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single-pubs.html %}
{% endfor %}

<h2 class="archive__subtitle">Theses</h2> 
{% for post in site.theses reversed %}
  {% include archive-single-pubs.html %}
{% endfor %}

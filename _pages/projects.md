---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
redirect_from:
  - /project
---

{% include base_path %}

<h2 class="archive__subtitle">MT/NLP Projects</h2> 
{% for post in site.projects reversed %}
  {% if post.tag == 'mt_project' %}
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}

<h2 class="archive__subtitle">Older Projects</h2> 
{% for post in site.projects reversed %}
  {% if post.tag == 'older_project' %}
    {% include archive-single-talk.html %}
  {% endif %}
{% endfor %}

<hr/>

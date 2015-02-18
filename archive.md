---
layout: page
title: Archive
---


{% for post in site.posts %}
  <p style="margin-left: 1rem; margin-bottom: -1rem;">* {{ post.date | date_to_string }} &raquo; [ {{ post.title }} ]({{ post.url }})</p>
{% endfor %}
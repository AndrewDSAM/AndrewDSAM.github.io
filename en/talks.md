---
layout: archive
title: "Talks and Presentations"
permalink: /en/talks/
author_profile: true
---

{% if site.talkmap_link == true %}
  <p style="text-decoration:underline;"><a href="/talkmap.html">See a map of all the places I have given a talk.</a></p>
{% endif %}

{% for post in site.talks reversed %}
  {% include archive-single.html %}
{% endfor %}

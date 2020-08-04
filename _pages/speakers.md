---
layout: page
title: "A list of animals"
permalink: "/speakers/"
---

{% for speaker in site.speakers %}
  <div class="speaker">
    <h2><a href="{{ speaker.url }}">{{ speaker.title }}</a></h2>
  </div>
{% endfor %}

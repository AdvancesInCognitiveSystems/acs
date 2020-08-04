---
layout: page
title: Invited Talks
permalink: "/speakers/"
---

{% for speaker in site.speakers %}
  <div class="speaker">
    <p>{{ speaker.label }} &nbsp; {{ speaker.time }} &nbsp; {{ speaker.name }} &nbsp; <a href="/acs{{ speaker.url }}">{{ speaker.title }}</a></p>
  </div>
{% endfor %}

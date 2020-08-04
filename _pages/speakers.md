---
layout: page
title: "A list of animals"
permalink: "/speakers/"
---

{% for speaker in site.speakers %}

<a href="{{ speaker.url | prepend: site.baseurl }}">
  <h2>{{ speaker.title }}</h2>
</a>

<p class="post-excerpt">{{ speaker.description | truncate: 160 }}</p>

{% endfor %} 

---
layout: default
title: About
content_source: about-me.md
---

{% assign source_file = site.pages | where: "path", "_content/about-me.md" | first %}

{% if source_file %}
  {{ source_file.content }}
{% else %}
  <p>Content is being updated. Please check back soon.</p>
{% endif %}
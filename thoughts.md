---
layout: default
title: Thoughts
content_source: thoughts-main.md
---

{% assign source_file = site.pages | where: "path", "_content/thoughts-main.md" | first %}

{% if source_file %}
  {{ source_file.content }}
{% else %}
  <p></p>
{% endif %}
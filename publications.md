---
layout: default
title: Publications
content_source: publications-list.md
---

{% assign source_file = site.pages | where: "path", "_content/publications-list.md" | first %}

{% if source_file %}
  {{ source_file.content }}
{% else %}
  <p>List of publications is being compiled.</p>
{% endif %}
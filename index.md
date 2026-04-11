---
layout: home
title: Home
---

{% assign source_file = site.pages | where: "path", "_content/home-content.md" | first %}

{% if source_file %}
  {{ source_file.content }}
{% else %}
  Welcome.
{% endif %}
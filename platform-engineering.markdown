---
layout: page
title: Platform Engineering
permalink: /platform-engineering/
---

# Platform Engineering

Essays on infrastructure-as-code, developer platforms, automation, internal tooling, and the systems that help engineering organizations scale.

{% for post in site.categories.platform-engineering %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

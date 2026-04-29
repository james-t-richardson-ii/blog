---
layout: page
title: Engineering Leadership
permalink: /leadership/
---

# Engineering Leadership

Essays on the systems, habits, and decisions that help engineering teams scale.

Engineering leadership is not just people management. It is the work of creating clarity, improving decision quality, building durable systems, and helping teams operate with more trust and less friction.

## Topics I write about here

- Code review culture
- Release management
- Technical decision-making
- Organizational design
- Developer experience
- Platform adoption
- Operating models for growing teams

## Essays

{% for post in site.categories.leadership %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

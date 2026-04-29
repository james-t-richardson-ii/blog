---
layout: page
title: Platform Engineering
permalink: /platform-engineering/
---

# Platform Engineering

Essays on infrastructure-as-code, developer platforms, automation, internal tooling, and the systems that help engineering organizations scale.

Platform engineering is not just building internal tools. It is the practice of turning repeated operational patterns into reliable, paved-road systems that reduce cognitive load and improve delivery.

## Topics I write about here

- Terraform, Terragrunt, and infrastructure workflows
- Moving away from click-ops
- Developer platforms and self-service
- GitHub Actions and platform automation
- Testing infrastructure beyond plan output
- Scaling operational standards across teams

## Essays

{% for post in site.categories.platform-engineering %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

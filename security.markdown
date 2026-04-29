---
layout: page
title: Security & Compliance
permalink: /security/
---

# Security & Compliance

Essays on secure delivery, regulated engineering environments, secrets management, software supply chain, exploit development, enumeration, and practical security culture.

Security works best when it is built into the way engineering teams already deliver software. The goal is not to slow teams down. The goal is to make safe paths easier to follow than unsafe ones.

## Topics I write about here

- Vault integration patterns
- GitHub Actions security
- Exploit development and enumeration
- Software supply chain controls
- Regulated SaaS environments
- Compliance-aware platform design

## Essays

{% for post in site.categories.security %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

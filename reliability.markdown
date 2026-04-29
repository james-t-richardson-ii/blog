---
layout: page
title: Reliability & Observability
permalink: /reliability/
---

# Reliability & Observability

Essays on production operations, observability strategy, incident response, logging, metrics, tracing, compliance, and the realities of running software systems at scale.

Reliability is not a tool choice. It is an operating discipline that connects architecture, ownership, feedback loops, and business risk.

## Topics I write about here

- Observability strategy
- New Relic, Grafana, Prometheus, Loki, and Splunk
- Log retention and compliance
- Incident response
- SLOs and operational maturity
- Production readiness

## Essays

{% for post in site.categories.reliability %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

---
layout: page
title: AI & Operations
permalink: /ai-ops/
---

# AI & Operations

Essays on practical AI adoption inside engineering organizations: AI-assisted operations, knowledge systems, automation agents, incident response, developer productivity, and the changing role of platform teams.

AI in operations is not just about smarter alerts. The real opportunity is turning operational knowledge into systems that help teams make better decisions, reduce toil, and respond faster.

## Topics I write about here

- Developing an AI-Ops strategy
- AI/ML in operational engineering teams
- Knowledge capture and retrieval for engineering organizations
- Agent-assisted workflows
- Moving from dashboards to decisions
- Human-in-the-loop automation

## Essays

{% for post in site.categories.ai-ops %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%B %-d, %Y" }}
{% endfor %}

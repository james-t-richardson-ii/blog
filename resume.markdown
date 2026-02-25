---
layout: page
title: Resume
permalink: /resume/
---

# James T. Richardson II

**Principal Engineering Leader & Distributed Systems Architect**

Git Platforms • Enterprise Automation • Cloud Infrastructure

Colorado Springs, CO
[james@richardsons.us](mailto:james@richardsons.us) · [LinkedIn](https://www.linkedin.com/in/the-real-james-richardson/) · [GitHub](https://github.com/james-t-richardson-ii/james-t-richardson-ii)

---

## Principal-Level Engineering Leader & Systems Architect

Engineering leader and hands-on platform architect with 20+ years building and operating distributed systems, SCM platforms, and enterprise automation frameworks. Experienced leading globally distributed engineering teams while remaining deeply engaged in architecture reviews, pull requests, and systems-level design decisions.

Currently leading enterprise-wide GitHub Enterprise consolidation (20,000+ repositories) and designing policy-driven automation systems that improve governance, reliability, and developer productivity at scale.

---

## Core Expertise

- Distributed Systems Architecture
- Git & SCM Governance at Enterprise Scale
- Production Systems Troubleshooting (networking, storage, caching, load-balancing)
- Kubernetes & Containerized Platforms
- GitHub Enterprise, Actions, Apps & API Automation
- Infrastructure-as-Code (Terraform / Terragrunt)
- High-Performance & Air-Gapped Systems
- Observability & SRE Practices
- Organizational Technical Leadership

---

## Platform Architecture & Systems Engineering

Hands-on development across Bash, Terraform (HCL), Docker, GitHub Actions (YAML), and GitHub APIs, building production automation systems used across enterprise engineering organizations.

### GitHub Enterprise Control Plane

- Architected and implemented an enterprise IssueOps control plane leveraging GitHub Issues, Actions, and APIs to automate repository lifecycle management, governance, and large-scale migrations.
- Designed a matrix-based multi-repository migration engine with controlled concurrency (max-parallel, fail-fast orchestration).
- Automated GitHub Enterprise Importer (GEI) workflows, including LFS-aware migration handling.
- Implemented deterministic naming and prefix governance logic with org-level custom property schemas and admin-team authorization mapping.
- Migrating 20,000+ repositories from 20+ independent GitHub, GitLab, Bitbucket, and SVN instances into GitHub Enterprise Managed Users (EMU).
- Realized $300,000+ in direct licensing and hosting cost savings through system consolidation.
- Retired legacy Bitbucket and SVN infrastructure, reducing operational overhead and improving security posture.

### Terraform PR Automation Platform

- Architected containerized Atlantis platform for Terraform/Terragrunt PR automation.
- Designed multi-stage Docker builds with strict version pinning via centralized configuration.
- Integrated Atlantis, Terraform, Terragrunt, Helm, and kubectl into unified runtime environment.
- Implemented s6-overlay service supervision for production-grade reliability.
- Enforced CI quality gates (hadolint, shellcheck, actionlint, yamllint) via pre-commit and pipeline automation.
- Standardized infrastructure PR workflows across teams, increasing determinism and reducing drift.

### Shared Automation Framework

- Designed modular cross-shell automation library supporting Bash and Zsh with consistent APIs.
- Implemented defensive scripting standards.
- Created reusable modules for logging, assertions, AWS wrappers, file operations, and structured output.
- Eliminated redundant operational tooling and increased reliability across engineering teams.

---

## Professional Experience

### Senior Engineering Manager

**Ping Identity** | 2021 – Present
Scope: 4–15 direct reports | Enterprise Identity Platform | Impact across 1,000+ engineers

Lead distributed engineering teams responsible for regulated platform architecture, SRE operations, SCM governance, and internal developer platforms supporting large-scale SaaS identity systems.

#### FedRAMP Architecture & Shared Services Model

- Brought in to lead engineering for initial FedRAMP offering; partnered with security, 3PAO auditors, and business leadership to architect shared-services model within FedRAMP boundary.
- Designed scalable multi-tenant shared services architecture enabling compliant customer onboarding without duplicating core infrastructure.
- Redefined AWS Organization strategy and governance model to support regulated workloads.
- Built and operationalized an AWS Account Factory to provision secure, policy-compliant accounts across business units.
- Balanced compliance, operational efficiency, and developer velocity within regulated environments.

#### SRE & Reliability Leadership

- Managed SRE teams supporting largest single-tenant SaaS environments.
- Reduced customer-facing incidents by 10% through operational rigor, improved observability, and post-incident process refinement.
- Led root-cause investigations across networking, container orchestration, storage, CI/CD, and application services layers.
- Implemented SRE-aligned practices including SLIs/SLOs, incident standardization, and reliability guardrails.

#### Post-M&A Platform Consolidation & Operationalization

- Led consolidation of security analysis, reporting platforms, and developer tooling following acquisition integration.
- Standardized operational models across inherited systems, reducing duplication and increasing consistency.
- Operationalized internal services to improve reliability, maintainability, and supportability.

#### Enterprise SCM Consolidation & GitHub Architecture

- Architected and executed enterprise-wide SCM consolidation into GitHub Enterprise Managed Users (EMU).
- Migrating 20,000+ repositories from 20+ independent GitHub, GitLab, Bitbucket, and SVN instances.
- Designed self-service policy management and automated migration tooling.
- Realized $300,000+ in direct licensing and hosting cost savings.
- Retired legacy SCM systems, improving governance and security posture across 1,000+ engineers.

#### Secure Software Signing Platform

- Designed and implemented centralized software signing service accessible via Jenkins, GitLab, and GitHub pipelines.
- Enabled use-case-based key selection and secure digital signing across development workflows.
- Reduced risk associated with distributed key management and improved compliance alignment.

#### Technical Leadership

- Mentor engineers from junior through principal levels.
- Regularly review pull requests and architectural designs.
- Drive cross-functional technical discussions across engineering, security, and product leadership.

---

### Engineering Leader
**Flatirons Solutions** | 2020 – 2021
Scope: 35 engineers across North America, Europe, and India

- Led modernization of mission-critical aviation software from on-premise deployments to cloud-native SaaS offerings.
- Directed containerization and Kubernetes adoption across legacy systems.
- Designed cloud storage and networking architectures for high-availability SaaS environments.
- Established GitOps-driven CI/CD pipelines.
- Led cross-region engineering collaboration and cloud-native skill development.

---

### Engineering Leader / Principal Technical Contributor
**Maxar Technologies (DigitalGlobe)** | 2010 – 2020

- Designed and built HPC clusters for large-scale data processing.
- Led enterprise AWS adoption and cloud migration strategy.
- Developed Infrastructure-as-Code frameworks and custom CI/CD pipelines for connected and air-gapped environments.
- Consolidated enterprise source control systems into GitHub.
- Led SAFe agile transformation across engineering departments.
- Troubleshot distributed systems across networking, storage, caching, and compute layers in mission-critical environments.

---

## Certifications

- GitHub Foundations Certification
- Advanced GitHub Actions Training
- GitHub Copilot & AI Workflow Integration Training

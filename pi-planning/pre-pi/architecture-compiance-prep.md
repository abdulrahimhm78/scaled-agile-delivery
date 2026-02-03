# Architecture & Compliance Preparation (Enterprise Standard)

This document defines the minimum expectations for preparing architecture and compliance readiness before work enters a sprint or program increment in regulated, enterprise environments.

---

## Purpose

To ensure solution design, security, and regulatory obligations are understood early, reducing rework, audit findings, and late-stage delivery risk.

---

## Scope

Applies to:
- Enterprise Scrum teams
- Platform and shared services teams
- Programs operating under regulatory, security, or architectural governance

---

## When This Applies

Architecture and Compliance Preparation is required:
- Before features are committed to a sprint
- Before PI Planning commitments
- When introducing new technologies, integrations, or data flows
- When changes impact security, privacy, or regulatory controls

---

## Architecture Readiness Checklist

A backlog item is architecturally ready when:

- Solution approach is documented (high-level design)
- Impacted systems and integrations are identified
- Non-functional requirements are understood (performance, scalability, availability)
- Data flows are defined (ingress, egress, storage)
- Technical dependencies are identified and validated
- Alignment with enterprise architecture standards is confirmed
- Architecture review (if required) is completed or scheduled

---

## Compliance Readiness Checklist

A backlog item is compliance-ready when:

- Regulatory impact is assessed (e.g., data privacy, audit, retention)
- Security controls are identified (authentication, authorization, encryption)
- Data classification is confirmed (PII, PHI, PCI, internal)
- Logging, monitoring, and audit requirements are defined
- Required approvals or evidence expectations are known
- Compliance risks are documented with mitigation plans

---

## Required Artifacts

The following artifacts should exist before commitment:

- Architecture overview (diagram or documented design)
- Compliance impact assessment (lightweight where possible)
- Security considerations summary
- Dependency and risk register entry (if applicable)
- Traceability to enterprise standards or policies

---

## Roles and Accountability

**Product Owner**
- Ensures business scope aligns with architectural and compliance constraints
- Prioritizes work that is ready from a governance perspective

**Scrum Master**
- Enforces readiness expectations
- Surfaces risks and escalates gaps early
- Ensures preparation does not become a bottleneck

**Architecture / Security Partners**
- Provide timely guidance and reviews
- Define guardrails, not detailed execution plans

**Delivery Team**
- Incorporates architectural and compliance requirements into implementation
- Maintains documentation and evidence as work progresses

---

## Common Anti-Patterns

- Treating architecture review as a post-development activity
- Discovering compliance requirements after development starts
- Relying on verbal approvals without documentation
- Over-engineering designs beyond business need
- Delaying risk escalation until late in the sprint or PI

---

## Success Indicators

- Reduced rework due to late governance findings
- Predictable sprint and PI commitments
- Fewer audit observations and security defects
- Faster approval cycles through prepared artifacts
- Clear alignment between delivery and enterprise standards

---

## Guiding Principle

Architecture and compliance are enablers of sustainable delivery.  
Preparation should be **lightweight, intentional, and early**—never reactive.

# Scaled Agile Delivery

Scaled Agile Delivery defines **program-level execution practices**
for coordinating delivery across multiple Scrum teams operating in
complex enterprise environments.

This repository focuses on **alignment, dependency management, risk control,
and executive visibility** once teams are already operating with
strong Scrum fundamentals.

---

## Purpose

The purpose of this repository is to:

- Enable predictable execution across multiple teams
- Coordinate dependencies without disrupting team autonomy
- Surface delivery risk early and visibly
- Provide clear, executive-ready delivery insights
- Support PI-level planning and execution discipline

This repository exists **above team-level Scrum execution**.

---

## Scope

This repository governs **program and ART-level delivery execution**, including:

- PI Planning facilitation and execution
- Cross-team dependency identification and tracking
- Program-level risk identification and escalation
- Delivery health and progress visibility
- Alignment between teams, leadership, and stakeholders

---

## Out of Scope

This repository intentionally **does not define**:

- Scrum roles or responsibilities
- Scrum events or ceremonies
- Definition of Ready or Definition of Done
- Team-level metrics or Jira workflows

Those concerns are owned by foundational repositories.

---

## Repository Structure

### `/pi-planning`
Defines PI Planning execution standards.

Includes:
- Pre-PI readiness expectations
- Day 1 and Day 2 facilitation guidance
- Commitment alignment
- Risk identification and mitigation

Focus:
- Alignment over optimism
- Realistic planning over aspirational commitments

---

### `/dependencies`
Defines dependency management practices.

Includes:
- Cross-team dependency identification
- Dependency ownership and tracking
- Visibility and escalation patterns

Focus:
- Early discovery
- Explicit ownership
- No hidden dependencies

---

### `/risk-management`
Defines delivery risk management practices.

Includes:
- Program-level risk identification
- Escalation thresholds
- Mitigation ownership

Focus:
- Surfacing risk early
- Avoiding last-minute surprises
- Enabling leadership decision-making

---

### `/program-visibility`
Defines executive-facing delivery visibility.

Includes:
- Program health summaries
- Predictability indicators
- Risk and dependency reporting

Focus:
- Transparency without noise
- Insight over raw data
- Trend-based decision support

---

## Relationship to Other Repositories

This repository is part of a layered enterprise Agile operating model.

### 1. Enterprise Scrum Playbook (Foundation)
**Repository:** `enterprise-scrum-playbook`

Provides:
- Scrum roles and accountability
- Scrum event standards
- Definition of Ready and Definition of Done

Dependency:
> Scaled execution assumes teams already follow disciplined Scrum practices.

---

### 2. Agile Metrics and Flow (Measurement)
**Repository:** `agile-metrics-and-flow`

Provides:
- Flow metrics
- Predictability indicators
- Outcome-based reporting

Dependency:
> Program visibility relies on clean, consistent metrics produced by disciplined teams.

---

### 3. Jira Governance (Tooling Enforcement)
**Repository:** `jira-governance`

Provides:
- Workflow enforcement
- Data integrity guardrails
- Tooling alignment with process

Dependency:
> Tooling enforces the behaviors defined by program and team standards.

---

## Intended Audience

This repository is intended for:

- Release Train Engineers (RTEs)
- SAFe Scrum Masters
- Program Managers
- Delivery Leads
- Enterprise Agile Coaches

It assumes strong Scrum fundamentals and is **not an introductory guide**.

---

## Guiding Principle

**Scale amplifies behavior.**

Strong team discipline scales predictably.  
Weak team discipline scales chaos.

This repository exists to ensure scale increases **clarity and control**
— not confusion and noise.

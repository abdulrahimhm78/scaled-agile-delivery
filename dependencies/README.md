# Dependency Management (Enterprise & Scaled Agile)

Effective dependency management ensures predictable delivery by identifying, tracking, and resolving cross-team, cross-system, and external dependencies early and continuously.

---

## Purpose

To proactively manage dependencies that impact delivery flow, reduce risk, and enable coordinated execution across teams and programs.

---

## Dependency Types

- **Team-to-Team** – Work required from another delivery team
- **System-to-System** – Integration or platform dependencies
- **External Vendor** – Third-party deliverables or approvals
- **Governance / Compliance** – Security, legal, audit, or regulatory gates
- **Data / Environment** – Test data, environments, or infrastructure readiness

---

## Ownership & Accountability

- **Scrum Master**
  - Facilitates dependency identification and visibility
  - Ensures dependencies are reviewed in ceremonies
  - Drives escalation when blocked

- **Product Owner**
  - Prioritizes work considering dependency risk
  - Aligns sequencing with business outcomes

- **Release Train Engineer / Program Lead**
  - Coordinates cross-team dependencies
  - Owns program-level resolution and escalation

- **Delivery Teams**
  - Surface dependencies early
  - Actively collaborate to resolve them

---

## Identification Points

Dependencies must be identified during:
- Backlog refinement
- Sprint Planning
- PI Planning (Program-level)
- Daily Scrum (emerging blockers)

---

## Dependency Tracking Standards

Each dependency must include:
- Clear description
- Owning team or external party
- Required-by date
- Impact if delayed
- Current status (Open / At Risk / Resolved)
- Explicit owner

Recommended artifacts:
- Program dependency board
- RAID log (Risks, Assumptions, Issues, Dependencies)
- Jira dependency links or labels

---

## Resolution Workflow

1. **Identify** – Capture dependency as soon as discovered
2. **Assess** – Determine impact, urgency, and risk level
3. **Align** – Coordinate with owning party on resolution plan
4. **Track** – Monitor status daily until resolved
5. **Escalate** – Raise unresolved or high-risk dependencies promptly
6. **Close** – Confirm resolution and unblock impacted work

---

## Escalation Triggers

Escalate immediately when:
- Dependency threatens sprint or PI objectives
- No owner is assigned within 24–48 hours
- External commitments are missed
- Risk exposure increases over time

---

## Metrics & Signals

- Number of open dependencies per sprint / PI
- Dependency aging
- % dependencies resolved as planned
- Delivery delays caused by dependencies

---

## Good Practices

- Visualize dependencies early and publicly
- Assign a single accountable owner
- Resolve dependencies before pulling work into a sprint
- Review dependencies in every Scrum-of-Scrums / program sync
- Treat unresolved dependencies as delivery risks

---

## Common Anti-Patterns

- Discovering dependencies mid-sprint
- Assuming “someone else” owns the dependency
- Tracking dependencies informally or verbally
- Delaying escalation to avoid conflict
- Planning work without dependency validation

---

## Guiding Principle

**Unmanaged dependencies create hidden risk. Visible dependencies enable predictable delivery.**

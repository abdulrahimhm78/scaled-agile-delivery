# Dependency Identification (Enterprise Standard)

## Purpose
To proactively identify, document, and manage dependencies that may impact delivery timelines, scope, quality, or value realization across teams, systems, and stakeholders.

Effective dependency identification enables early risk mitigation, realistic planning, and predictable execution—especially in multi-team and scaled Agile environments.

---

## What Is a Dependency
A dependency exists when the progress, start, or completion of work is reliant on another team, system, decision, or external factor.

Dependencies can exist **within a team**, **across teams**, or **outside the delivery organization**.

---

## Dependency Categories

### 1. Team-to-Team Dependencies
- Shared components or services
- API contracts between teams
- Upstream/downstream feature sequencing
- Shared environments or test data

### 2. Technical Dependencies
- Platform readiness
- Infrastructure provisioning
- Security reviews or approvals
- Legacy system constraints
- Data availability or migration timing

### 3. Business Dependencies
- Stakeholder decisions
- Regulatory or compliance input
- Funding or budget approvals
- Vendor commitments

### 4. External Dependencies
- Third-party vendors
- External partners
- Open-source updates
- Organizational change initiatives

---

## When to Identify Dependencies

Dependencies must be identified at **multiple levels and events**:

- Backlog Refinement
- Sprint Planning
- PI Planning (or Quarterly Planning)
- Risk and Dependency Reviews
- During execution (emergent dependencies)

Dependency identification is **continuous**, not a one-time activity.

---

## Dependency Identification Checklist

A backlog item is considered dependency-aware when:

- ☐ Upstream and downstream teams are identified  
- ☐ Required inputs are clearly defined  
- ☐ Output consumers are known  
- ☐ Timing constraints are documented  
- ☐ Ownership for resolution is assigned  
- ☐ Risk of delay is assessed  

---

## Documentation Standards

All identified dependencies must be documented with:

- Dependency description
- Source team / system
- Target team / system
- Required-by date
- Risk level (Low / Medium / High)
- Owner responsible for follow-up
- Current status

Dependencies should be visible in:
- Jira (linked issues, labels, or dependency fields)
- Program boards
- Dependency trackers
- PI or sprint planning artifacts

---

## Roles and Responsibilities

### Scrum Master
- Facilitate early identification during refinement and planning
- Ensure dependencies are visible and actively tracked
- Escalate unresolved or high-risk dependencies
- Drive follow-through and accountability

### Product Owner
- Prioritize work considering dependency impact
- Align sequencing with business outcomes
- Engage stakeholders for decision-related dependencies

### Delivery Team
- Surface technical and execution dependencies early
- Collaborate with dependent teams
- Provide realistic effort and timing inputs

### RTE / Program Leadership (Scaled Context)
- Own cross-team dependency coordination
- Maintain program-level visibility
- Enable resolution through leadership alignment

---

## Good Practices

- Identify dependencies before committing to work
- Treat dependencies as risks until resolved
- Assign a single owner per dependency
- Review dependency status at least weekly
- Visualize dependencies, not just list them
- Close dependencies explicitly once resolved

---

## Common Mistakes

- Discovering dependencies mid-sprint
- Assuming another team is “already working on it”
- Tracking dependencies informally or verbally
- Failing to assign ownership
- Ignoring dependency risk during commitment

---

## Guiding Principle
If a dependency is not visible, it is unmanaged.  
Unmanaged dependencies are the leading cause of missed commitments in enterprise Agile delivery.

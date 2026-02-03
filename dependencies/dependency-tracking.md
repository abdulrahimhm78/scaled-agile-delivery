# Dependency Tracking (Enterprise Delivery)

## Purpose
Dependency tracking ensures visibility, ownership, and timely resolution of cross-team, cross-system, and external dependencies that impact delivery predictability in scaled Agile environments.

## Definition
A dependency is any work item, decision, resource, or external input required by one team that is owned or delivered by another team, system, vendor, or organization.

## Types of Dependencies
- **Cross-Team** – Between Agile teams on the same ART or program
- **Cross-ART / Program** – Between multiple Agile Release Trains or portfolios
- **External** – Vendors, third parties, regulatory bodies
- **Technical** – Shared services, APIs, environments, data contracts
- **Business / Decision** – Funding, approvals, prioritization decisions

## Dependency Lifecycle
1. **Identify** – During backlog refinement, PI Planning, or Sprint Planning  
2. **Log** – Capture in a centralized dependency register or tool  
3. **Assign Ownership** – Clear owning team and accountable owner  
4. **Assess Risk** – Impact, urgency, and delivery risk  
5. **Track** – Monitor status and aging regularly  
6. **Resolve or Escalate** – Act early to avoid delivery impact  
7. **Close** – Confirm resolution and downstream readiness  

## Required Dependency Attributes
Each dependency must include:
- Description
- Requesting team
- Owning team or party
- Needed-by date
- Impact if delayed
- Current status (Open / At Risk / Blocked / Resolved)
- Owner
- Escalation path (if applicable)

## Cadence and Governance
- Reviewed **weekly** at program-level syncs (e.g., Scrum of Scrums)
- Reviewed **daily** by teams if blocking sprint progress
- Reviewed at **PI-level** during PI Planning and ART syncs
- Aged dependencies (>2 sprints) require escalation

## Roles and Responsibilities
- **Team** – Identify and raise dependencies early
- **Scrum Master** – Track, surface risks, and drive follow-ups
- **RTE / Program Lead** – Resolve cross-team and systemic blockers
- **Product Management** – Reprioritize work based on dependency risk
- **Leadership** – Remove organizational or funding constraints

## Good Practices
- Track dependencies visually (boards, tables, or dashboards)
- Assign a single accountable owner per dependency
- Focus on resolution, not reporting
- Address dependencies before they become blockers
- Use PI Planning to eliminate dependencies upfront

## Common Anti-Patterns
- Tracking dependencies only after they block delivery
- No clear owner or escalation path
- Treating dependencies as informational only
- Allowing long-lived unresolved dependencies
- Relying on verbal agreements without documentation

## Success Indicators
- Fewer sprint carryovers due to dependencies
- Reduced dependency aging
- Improved delivery predictability
- Clear ownership and fast escalation paths
- Dependencies resolved before sprint impact

## Guiding Principle
Unmanaged dependencies create hidden risk. Visibility, ownership, and early action are mandatory for predictable enterprise delivery.

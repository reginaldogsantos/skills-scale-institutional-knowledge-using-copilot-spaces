# OctoAcme Project Management Docs

Welcome! This README provides an overview and links to all core program management documents for OctoAcme projects.

## Summary of Project Management Processes

OctoAcme follows a structured five-stage project lifecycle designed to maximize customer value while maintaining clear ownership and data-driven decision-making. The organization applies core principles of **customer-first delivery**, **iterative increments**, and **psychological safety** across all cross-functional projects.

### Lifecycle Stages

Each project progresses through the following stages:

1. **Initiation** — Validate business need, align stakeholders, and confirm measurable success metrics
2. **Planning** — Break work into shippable increments, identify dependencies, and align timelines
3. **Execution** — Build, test, review, and iterate with daily standups and regular demos
4. **Release** — Deploy to production safely with pre-release checks and rollback plans
5. **Close & Retrospective** — Capture learnings and convert them into actionable improvements

### Core Principles

- **Customer-first**: Value and evidence drive all prioritization decisions
- **Iterative delivery**: Deliver small, testable increments with frequent review cycles
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and transparent risk communication

### Roles & Responsibilities

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design, maintain testability and code quality
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs, approvals, and strategic guidance

### Communication Cadence

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Twice-weekly standups** — Delivery team synchronization (or as agreed)
- **Weekly PM + PdM sync** — Leadership alignment on priorities and risks
- **Weekly stakeholder updates** — Status, risks, and decisions needed
- **Monthly stakeholder briefings** — Strategic updates and roadmap alignment
- **Ad-hoc escalations** — For critical issues following a three-level escalation path

### Quality & Execution Standards

- **Small PRs** (≤ 400 lines) with clear issue links and acceptance criteria
- **Automated CI/CD** — Tests, linting, and security scans before review
- **Minimum one approval** — Before merging (team-defined policy)
- **Multi-layer testing** — Unit tests, integration tests, end-to-end smoke tests for critical flows
- **Definition of Done** — Documented upfront during planning; enforced before closure
- **Manual QA** — Feature acceptance validation when needed

### Risk & Dependency Management

- **Risk Register** — Maintained with ID, description, impact, likelihood, owner, and mitigation plan
- **Three-level escalation** — Team triage → PM escalation → Sponsor involvement
- **Weekly reviews** — Risks and blockers reviewed at weekly syncs
- **Dependency mapping** — Cross-team dependencies marked and escalated proactively

### Release & Deployment

- **Release types** — Patch (hotfixes), Minor (incremental features), Major (significant changes)
- **Pre-release requirements** — All acceptance criteria met, CI passing, release notes drafted, rollback plan documented
- **Staged deployment** — Staging with smoke tests before production deployment
- **Post-deploy verification** — Automated and manual checks to confirm success
- **Rollback & incident response** — Blameless retrospectives to extract learning

### Continuous Improvement

- **Sprint/milestone retrospectives** — 45–75 minutes to capture learnings and improvements
- **Action item tracking** — Assigned owners, due dates, and success criteria
- **Feedback loops** — Improvements feed back into project backlog and process docs
- **Impact measurement** — Track success of action items and celebrate wins

---

## Docs Index

Navigate to each guide for detailed workflows, checklists, templates, and examples:

- **[Project Management Overview](octoacme-project-management-overview.md)** — High-level introduction to OctoAcme's approach, roles, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate business need, align stakeholders, and authorize work
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, estimate scope, and define release timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Day-to-day execution, team rhythm, quality standards, and blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Risk identification, lifecycle management, and stakeholder communication strategies
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardized release types, pre-release requirements, and deployment safety
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Running retrospectives and tracking action items for ongoing improvement
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Detailed role definitions, responsibilities, and typical communication patterns

---

## How to Use These Docs

- **For new team members**: Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the framework, then reference specific guides as you work through each project phase.
- **For project managers**: Use the initiation, planning, and risk management guides as your primary reference. Keep the Project Charter and Risk Register updated in your project repo.
- **For product managers**: Reference the Initiation and Planning guides to define success metrics and prioritize the backlog.
- **For developers**: Focus on the Execution & Tracking and Release guides. Familiarize yourself with Definition of Done, acceptance criteria, and testing standards.
- **For leadership**: Use the Overview, Risk Management, and Retrospective guides to stay informed on project health and organizational learning.

---

## Contributing to These Docs

Have feedback or want to suggest improvements? Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to request updates. All process improvements are tracked and reviewed collaboratively to keep OctoAcme's practices current and effective.

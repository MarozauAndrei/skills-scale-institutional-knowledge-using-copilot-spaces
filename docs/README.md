# OctoAcme Project Management Docs – README

Welcome! This README provides a navigable overview of the core project management processes used at OctoAcme. Use the links below to explore each topic in depth.

## Process Summary

**Purpose:** Deliver value through iterative, well-documented project execution, emphasizing clear ownership, stakeholder alignment, and continuous improvement.

### Key Principles
- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

### Lifecycle Overview
OctoAcme projects follow a structured five-phase lifecycle:

1. **Initiation** – Validate business need, align stakeholders, and create a lightweight one-pager with success criteria
2. **Planning** – Break work into shippable increments, identify dependencies, define acceptance criteria, and establish timelines
3. **Execution** – Build, test, review, and iterate through daily standups, sprint planning, and continuous quality checks
4. **Release** – Deploy staged rollouts, verify functionality, announce to stakeholders, and maintain rollback readiness
5. **Close & Retrospective** – Capture learnings, generate action items, and feed improvements back into processes

### Core Roles & Personas

- **Project Manager (PM)** – Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)** – Defines outcomes, prioritizes the backlog, and measures success
- **Developers** – Implement features, collaborate on design, and ensure testability
- **QA/Testing** – Validate quality and acceptance criteria
- **Stakeholders** – Provide inputs, approvals, and business context

### Key Artifacts

- Project Charter / One-pager
- Prioritized backlog with acceptance criteria
- Risk Register (ID, description, impact, probability, owner, mitigation)
- Release notes and deployment plans
- Retrospective notes and action items
- Communication templates and status updates

### Execution Rhythm & Quality Practices

**Team Ceremonies:**
- Daily standups (15 min) – focus on blockers and dependencies
- Weekly PM-PdM sync – strategy and alignment
- Weekly delivery sync – progress and risk updates
- Sprint/iteration planning – backlog refinement and capacity planning
- Demos and retrospectives – at sprint/milestone close

**Quality & Testing:**
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows
- Security scanning in CI
- Manual QA for feature acceptance
- Small PRs (≤400 lines) with at least one approval required

**Risk & Communication:**
- Risk register maintained and reviewed weekly
- Escalation paths: Team → PM → Product Lead → Sponsor
- Weekly status updates to stakeholders
- Single source of truth for project status

---

## Links to Process Docs

Dive deeper into each area by exploring the detailed guides:

- **[Project Management Overview](octoacme-project-management-overview.md)** – High-level introduction to roles, principles, lifecycle, and key artifacts
- **[Project Initiation Guide](octoacme-project-initiation.md)** – Steps to validate ideas, align stakeholders, and confirm go/no-go
- **[Project Planning](octoacme-project-planning.md)** – Breaking work into increments, estimating scope, and building the release plan
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** – Day-to-day workflows, standups, PR conventions, and progress tracking
- **[Risks & Communication](octoacme-risks-and-communication.md)** – Risk management, escalation paths, and stakeholder communication templates
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** – Pre-release requirements, deployment checklist, and incident playbooks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** – Running retrospectives and converting learnings into action items
- **[Roles & Personas](octoacme-roles-and-personas.md)** – Detailed descriptions of PM, PdM, Developer, and Stakeholder responsibilities

---

## Getting Started

**New to OctoAcme projects?**
1. Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our principles and roles
2. If initiating a new project, read the [Project Initiation Guide](octoacme-project-initiation.md)
3. If planning or executing, reference the [Project Planning](octoacme-project-planning.md) and [Execution & Tracking](octoacme-execution-and-tracking.md) docs
4. Use the [Roles & Personas](octoacme-roles-and-personas.md) to understand your responsibilities and peers' roles

**Want to improve our processes?**
- Use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose updates
- Capture learnings in retrospectives and feed them back into these docs

---

## Questions?

If you have questions about OctoAcme's project management approach, refer to the specific doc linked above or reach out to your Project Manager or Product Lead.

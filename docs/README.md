# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation hub! This space organizes all key process documents and provides a brief summary of the OctoAcme approach so you can quickly find what you need.

## Project Management Process (Summary)

OctoAcme operates a structured, lifecycle-based project management approach that emphasizes customer value, iterative delivery, and clear ownership. The framework spans five core phases: **Initiation**, **Planning**, **Execution**, **Release**, and **Retrospective**. During initiation, teams validate business needs and align stakeholders around a lightweight Project One-pager that defines the problem, goals, success metrics, and key risks. Once approved, the planning phase breaks work into prioritized backlog items with clear acceptance criteria, estimates, and dependencies. This ensures that teams move into execution with a shared understanding of scope, timeline, and quality standards.

Execution follows an iterative, sprint-based cadence with defined team rhythms: daily standups (15 minutes) focus on progress and blockers, weekly delivery syncs review milestones and flag risks, and demos conclude each sprint. Work is tracked on a project board with columns spanning Backlog through Done, and pull requests are kept small (≤400 lines when possible) with at least one approval required before merge. Quality is embedded throughout via unit tests, integration tests, end-to-end smoke tests, and security scanning in CI pipelines. When teams encounter blockers, a three-level escalation path moves issues from team triage to PM escalation to sponsor-level intervention, ensuring visibility and rapid resolution.

OctoAcme defines clear roles that distribute accountability: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** own the vision, prioritize the backlog, and measure outcomes; **Developers** implement features and collaborate on design and testability; and **QA/Testing** validates quality against acceptance criteria. These roles communicate through weekly PM-PdM syncs, twice-weekly standups, monthly stakeholder updates, and ad-hoc escalations. Risk management is continuous—teams maintain a Risk Register during planning and update it weekly—and each risk is tracked through identification, assessment, mitigation, and monitoring stages.

Release and deployment are standardized to minimize production risk: pre-release requirements include passing CI, security scans, drafted release notes, and a documented rollback plan. Post-deployment verification and stakeholder announcement close the loop. Finally, retrospectives held after each sprint, release, or milestone capture learnings—what went well, what could improve, and prioritized action items with owners and timelines. This commitment to continuous improvement, combined with transparent communication and data-driven decision-making, ensures OctoAcme teams deliver reliable, customer-focused outcomes consistently.

## Key Principles

- **Customer-first:** Prioritize customer value and usability
- **Iterative delivery:** Deliver small, testable increments
- **Clear ownership:** Each project has a named Project Manager (PM) and Product Manager (PdM)
- **Data-informed decisions:** Measure impact and iterate based on evidence
- **Psychological safety:** Encourage feedback and learning

## Core Roles

- **Project Manager (PM):** Coordinates delivery, schedules, risks, and communications
- **Product Manager (PdM):** Defines outcomes, prioritizes backlog, and measures success
- **Developers:** Implement features, collaborate on design and testability
- **QA/Testing:** Validate quality and acceptance criteria
- **Stakeholders:** Provide inputs and approvals

## Docs Index

- [Project Management Overview](octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, roles, and key artifacts
- [Project Initiation Guide](octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [Project Planning](octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [Execution & Tracking](octoacme-execution-and-tracking.md) — Day-to-day execution, team rhythm, and progress tracking toward milestones
- [Risk Management & Communication](octoacme-risks-and-communication.md) — Identify, manage, and communicate risks and dependencies
- [Release & Deployment Guide](octoacme-release-and-deployment.md) — Standardized processes for releasing features to production safely
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [Roles and Personas](octoacme-roles-and-personas.md) — Detailed definitions of typical roles and responsibilities

## Getting Started

**New to OctoAcme?** Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand the framework.

**Starting a new project?** Follow the [Project Initiation Guide](octoacme-project-initiation.md) and then the [Project Planning](octoacme-project-planning.md) doc.

**Managing a project in progress?** Reference [Execution & Tracking](octoacme-execution-and-tracking.md) and [Risk Management & Communication](octoacme-risks-and-communication.md) for daily guidance.

**Preparing for release?** Check the [Release & Deployment Guide](octoacme-release-and-deployment.md).

**Wrapping up?** Learn how to run effective retrospectives in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md).

## Communication Cadence

- **Daily standups:** 15 minutes — focus on progress, blockers, dependencies
- **Weekly PM-PdM sync:** Alignment on priorities and risks
- **Twice-weekly delivery standups:** Track sprint progress and resolve blockers
- **Weekly stakeholder updates:** Status, risks, and decisions needed
- **Sprint/Milestone demos:** Show progress and gather feedback
- **Monthly stakeholder briefings:** High-level roadmap and strategic alignment

## Contributing & Feedback

These docs are living artifacts. If you identify gaps, improvements, or new processes to capture:
- Create an issue using the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
- Link your proposed updates to the relevant process doc
- Include rationale and suggested content

This ensures our institutional knowledge scales with the team and stays current with how we work.

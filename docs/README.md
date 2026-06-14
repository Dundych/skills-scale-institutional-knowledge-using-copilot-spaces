# OctoAcme Project Management Docs

This README provides a brief summary of OctoAcme's project management processes and links to the full process documents stored in the `docs/` folder.

## Overview of OctoAcme Project Management Processes

OctoAcme follows a structured, lifecycle-based approach to project management that emphasizes clear ownership, iterative delivery, and data-driven decisions. The framework spans five core phases:

- **Initiation**: Business needs are validated and stakeholders are aligned around a lightweight one-pager with clear success metrics and resource needs.
- **Planning**: Work is broken into shippable increments with prioritized backlogs, acceptance criteria, and defined milestones.
- **Execution & Tracking**: Teams deliver incrementally through daily standups, weekly syncs, and regular demos. Quality is ensured via CI/CD, automated testing, and code reviews.
- **Release & Deployment**: Deployments are standardized with pre-release checklists, smoke tests, and documented rollback playbooks to minimize risk.
- **Retrospectives & Continuous Improvement**: Learnings are captured and converted into actionable improvements for future initiatives.

### Key Roles & Communication

OctoAcme operates with well-defined roles—**Project Managers (PMs)** coordinate schedules and manage risks, **Product Managers (PdMs)** define outcomes and prioritize work, **Developers** implement features and collaborate on design, and **QA teams** validate quality. Communication happens through daily standups (15 min), weekly delivery syncs, and monthly stakeholder briefings. A structured escalation path (team-level → PM → Product Lead → sponsor) ensures blockers are addressed at the appropriate level.

### Quality & Risk Management

Quality and execution are built into every phase. Teams use GitHub Projects for workflow management, enforce small PRs (≤400 lines), require automated testing and security scanning in CI, and mandate at least one approval before merging. Risk management is continuous—risks are captured during planning, assessed for impact and likelihood, tracked in a risk register, and reviewed weekly. Success metrics and retrospectives ensure the team learns and improves systematically.

---

## Process Documentation

- [**OctoAcme Project Management Overview**](./octoacme-project-management-overview.md) — Concise introduction to OctoAcme's approach, roles, and key artifacts
- [**Project Initiation Guide**](./octoacme-project-initiation.md) — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- [**Project Planning**](./octoacme-project-planning.md) — Turn an approved initiative into an actionable plan and backlog for delivery
- [**Execution & Tracking**](./octoacme-execution-and-tracking.md) — Guidance for managing day-to-day execution and tracking progress toward milestones
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — How to identify, manage, and communicate risks and dependencies
- [**Release & Deployment Guide**](./octoacme-release-and-deployment.md) — Standardize releases and deployments to reduce risk and improve observability
- [**Retrospective & Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and convert them into actionable improvements
- [**Roles & Personas**](./octoacme-roles-and-personas.md) — Definitions of typical roles and responsibilities in OctoAcme projects

---

## Quick Links

- **New to OctoAcme?** Start with [OctoAcme Project Management Overview](./octoacme-project-management-overview.md)
- **Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md)
- **Planning sprint work?** See [Project Planning](./octoacme-project-planning.md)
- **Need help with risks or blockers?** Review [Risk Management & Communication](./octoacme-risks-and-communication.md)
- **Ready to release?** Check the [Release & Deployment Guide](./octoacme-release-and-deployment.md)

---

*Last updated: 2026-06-14*

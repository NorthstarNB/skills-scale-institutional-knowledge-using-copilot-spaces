# OctoAcme Project Management Processes

## Overview

OctoAcme follows a structured lifecycle approach to project management that emphasizes customer value, iterative delivery, and clear ownership. This README provides a high-level overview of our project management processes. For detailed guidance on each phase, please refer to the documentation files in this folder.

## Project Lifecycle

OctoAcme operates through five distinct phases:

1. **Initiation** — Validate the business need and authorize work
2. **Planning** — Turn approved initiatives into actionable plans and backlogs
3. **Execution** — Build, test, review, and iterate on features
4. **Release** — Deploy to production with reduced risk and improved observability
5. **Close & Retrospective** — Capture learnings and drive continuous improvement

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Key Roles and Personas

OctoAcme operates with distinct, well-defined roles:

- **Project Manager (PM)**: Coordinates delivery activities, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes the backlog, and measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validate quality and acceptance criteria
- **Stakeholders**: Provide inputs and approvals

For detailed role descriptions and responsibilities, see [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md).

## Team Rhythm and Communication

Teams operate with a consistent cadence:

- **Daily standups** (15 min) — Focus on progress, blockers, and dependencies
- **Weekly delivery sync** — Show progress, updates, and flagged risks
- **Demo/Review** — At the end of each sprint or milestone
- **Weekly stakeholder updates** — Status reports using standardized templates
- **Monthly stakeholder briefings** — High-level roadmap and business impact

All work is tracked through GitHub Projects with standardized columns: Backlog, Ready, In Progress, In Review, QA, and Done.

## Quality and Testing Standards

Quality is embedded throughout execution:

- **Unit tests** for new logic
- **Integration tests** where applicable
- **End-to-end smoke tests** for critical flows before release
- **Security scanning** in CI/CD pipeline
- **Manual QA** for feature acceptance when needed
- **Small PRs** (≤400 lines when possible) with at least one approval before merging
- **Automated CI testing** required before review

## Risk and Dependency Management

OctoAcme maintains a **Risk Register** that captures:
- Risk ID and description
- Impact (High/Med/Low) and likelihood (High/Med/Low)
- Owner and mitigation plan
- Status

Risks are reviewed weekly during delivery syncs and escalate through three levels:
1. **Level 1**: Team-level triage in daily standups
2. **Level 2**: PM escalates to Product Lead and dependent teams
3. **Level 3**: Sponsor-level escalation for business-impacting issues

## Continuous Improvement

After each sprint, release, or important milestone, teams conduct **retrospectives** (45–75 minutes) to:
- Discuss what went well
- Identify what could be improved
- Prioritize 2–3 action items with clear owners and due dates
- Measure impact of previous improvement actions

This cycle of planning, executing with clear quality gates, communicating progress, and retrospectively improving creates a sustainable operating model that balances delivery velocity with reliability and stakeholder trust.

## Documentation Structure

This folder contains detailed guidance for each phase and function:

- **[octoacme-project-management-overview.md](./octoacme-project-management-overview.md)** — Concise introduction to OctoAcme approach
- **[octoacme-project-initiation.md](./octoacme-project-initiation.md)** — Steps to validate and authorize work
- **[octoacme-project-planning.md](./octoacme-project-planning.md)** — Creating actionable plans and backlogs
- **[octoacme-execution-and-tracking.md](./octoacme-execution-and-tracking.md)** — Managing day-to-day execution
- **[octoacme-risks-and-communication.md](./octoacme-risks-and-communication.md)** — Risk and stakeholder management
- **[octoacme-release-and-deployment.md](./octoacme-release-and-deployment.md)** — Release and deployment procedures
- **[octoacme-retrospective-and-continuous-improvement.md](./octoacme-retrospective-and-continuous-improvement.md)** — Capturing learnings and improvements
- **[octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md)** — Role definitions and responsibilities

## Getting Started

For new team members and stakeholders:
1. Start with this README for a high-level overview
2. Review [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) for principles and key artifacts
3. Dive into phase-specific docs based on your current project stage
4. Use the role definitions to understand responsibilities and communication patterns

For questions or to propose updates to these processes, please use the [Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.

# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management process documentation. This folder contains standardized guidance for running projects, managing teams, and delivering value.

## Quick Start

OctoAcme follows a structured lifecycle approach to project delivery:

1. **Initiation** - Validate the problem and align stakeholders
2. **Planning** - Break work into actionable increments
3. **Execution** - Build, test, and iterate
4. **Release** - Deploy and verify in production
5. **Close & Retrospective** - Capture learnings and improve

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has named roles and clear accountability
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and continuous learning

## OctoAcme Project Management Overview

OctoAcme follows a structured, five-phase project lifecycle designed to deliver customer value through iterative, data-informed decisions. Projects move through **Initiation** (validating business need and stakeholder alignment), **Planning** (breaking work into shippable increments), **Execution** (building and testing incrementally), **Release** (deploying to production with minimal risk), and **Close & Retrospective** (capturing learnings). This approach emphasizes psychological safety, clear ownership, and continuous improvement, with each phase having defined deliverables, checklists, and decision gates to ensure projects remain aligned with business objectives and customer needs.

OctoAcme operates with clearly defined personas: **Project Managers** coordinate schedules, risks, and communications to deliver on time and within scope; **Product Managers** define what to build, prioritize the backlog, and measure outcomes; **Developers** implement features, write tests, and identify technical risks; and **QA/Testing** ensures quality and acceptance criteria validation. The team maintains a consistent communication cadence including daily standups (15 minutes, focused on blockers), weekly delivery syncs between PM and Product Lead, twice-weekly team standups, monthly stakeholder updates, and ad-hoc escalations. This rhythm keeps work visible, dependencies transparent, and enables rapid escalation when needed.

During execution, teams use a GitHub Projects-based workflow with columns (Backlog, Ready, In Progress, In Review, QA, Done) and maintain small PRs (≤400 lines) with linked issues and acceptance criteria. Quality is enforced through automated CI/CD (tests, linting, security scanning), manual QA for feature acceptance, and end-to-end smoke tests before release. Risk management is ongoing: risks are captured in a Risk Register (with ID, description, impact, likelihood, owner, and mitigation) and reviewed weekly. Three-level escalation paths address blockers: team triage, PM escalation to Product Lead and dependent teams, and sponsor-level escalation for business-impacting issues. Velocity, burndown, and key success metrics are tracked and reported to inform decisions.

Releases are standardized with pre-release requirements (passing CI, security scans, smoke tests, and documented rollback plans) and a deployment checklist to reduce production risk. After each sprint, release, or incident, retrospectives (45–75 minutes, using anonymous boards if needed) capture what went well and what can improve, with 2–3 prioritized action items added to the backlog with clear owners and due dates. This continuous improvement culture, supported by blameless post-incident retrospectives and measured impact of action items, ensures OctoAcme learns from every delivery cycle and iteratively strengthens its processes.

## Process Documents

- [Project Management Overview](./octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach, roles, and artifacts
- [Project Initiation Guide](./octoacme-project-initiation.md) - Steps to validate and authorize new work
- [Project Planning](./octoacme-project-planning.md) - Turn approved initiatives into actionable plans
- [Execution & Tracking](./octoacme-execution-and-tracking.md) - Day-to-day delivery management and progress tracking
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk identification and stakeholder communication
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) - Standardized release process and deployment checklists
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Capture learnings and drive improvements
- [Roles and Personas](./octoacme-roles-and-personas.md) - Definitions of key roles and responsibilities

## Issue Templates

When creating issues related to these processes, use the corresponding template:

- [Add/Update Content to Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) - Use this template to propose updates or additions to process documentation

## Navigation by Role

### For Project Managers
Start with [Project Management Overview](./octoacme-project-management-overview.md), then reference:
- [Project Initiation Guide](./octoacme-project-initiation.md) when starting new projects
- [Project Planning](./octoacme-project-planning.md) for scheduling and resource management
- [Execution & Tracking](./octoacme-execution-and-tracking.md) for day-to-day management
- [Risk Management & Communication](./octoacme-risks-and-communication.md) for escalation and stakeholder updates

### For Product Managers
Start with [Project Management Overview](./octoacme-project-management-overview.md), then reference:
- [Project Initiation Guide](./octoacme-project-initiation.md) for problem validation and success metrics
- [Project Planning](./octoacme-project-planning.md) for backlog prioritization and Definition of Done
- [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality and metrics tracking

### For Developers
Start with [Roles and Personas](./octoacme-roles-and-personas.md), then reference:
- [Project Planning](./octoacme-project-planning.md) for understanding acceptance criteria
- [Execution & Tracking](./octoacme-execution-and-tracking.md) for PR workflow and quality standards
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release requirements

### For QA/Testing
Reference:
- [Execution & Tracking](./octoacme-execution-and-tracking.md) for quality and testing requirements
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) for pre-release and smoke testing

## Getting Started

**New to OctoAcme?** Read the [Project Management Overview](./octoacme-project-management-overview.md) for a 10-minute introduction to our approach, roles, and key artifacts.

**Starting a new project?** Follow the [Project Initiation Guide](./octoacme-project-initiation.md) to validate the problem and get stakeholder alignment.

**Need to update these docs?** Use the [Add/Update Content to Process Docs](./../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template to propose changes.

# OctoAcme Project Management Docs

Welcome to OctoAcme's project management documentation. This guide provides an overview of how we run projects and links to detailed process documents for each stage of our project lifecycle.

## Project Management Overview

OctoAcme employs a structured yet iterative project management framework grounded in five core principles: **customer-first delivery**, **iterative development**, **clear ownership**, **data-informed decisions**, and **psychological safety**. 

We follow a complete project lifecycle spanning five key phases:

1. **Initiation** — Validate business need, establish measurable outcomes, and align stakeholders
2. **Planning** — Break work into shippable increments, identify dependencies, and define success criteria
3. **Execution** — Build, test, and review with daily standups and weekly syncs
4. **Release** — Deploy to production with pre-release checks, smoke tests, and rollback planning
5. **Retrospective** — Capture learnings and convert them into actionable improvements

Each phase includes formal gates and checklists that ensure alignment before proceeding. Key roles are clearly defined—Project Managers coordinate delivery and manage risks; Product Managers define success metrics and prioritize the backlog; Developers implement features with quality focus; and QA validates acceptance criteria.

Communication is structured through a consistent cadence: weekly PM-PdM syncs, twice-weekly delivery standups, monthly stakeholder updates, and ad-hoc escalations as needed. Risks are managed proactively via a Risk Register updated at every weekly sync, with clear escalation paths for blockers.

Quality assurance is embedded throughout execution via automated testing in CI/CD pipelines, code review requirements, and pre-release verification. Finally, we close the loop through structured retrospectives that feed action items back into the project backlog, creating a continuous improvement cycle.

## Process Documents

Use the links below to navigate to detailed guidance for each stage of the project lifecycle:

| Document | Purpose |
|----------|---------|
| [**Overview**](octoacme-project-management-overview.md) | Principles, core roles, key artifacts, communication cadence, and high-level lifecycle |
| [**Project Initiation**](octoacme-project-initiation.md) | Guidance and templates for validating and authorizing work, aligning stakeholders |
| [**Project Planning**](octoacme-project-planning.md) | Planning activities, backlog templates, release planning, and risk management |
| [**Execution & Tracking**](octoacme-execution-and-tracking.md) | Team rhythm, PR workflows, QA practices, metrics tracking, and escalation procedures |
| [**Risk Management & Communication**](octoacme-risks-and-communication.md) | Risk register, communication templates, escalation paths, and stakeholder updates |
| [**Release & Deployment**](octoacme-release-and-deployment.md) | Release types, pre-release checklists, deployment procedures, and incident playbook |
| [**Retrospective & Continuous Improvement**](octoacme-retrospective-and-continuous-improvement.md) | Running retrospectives, tracking improvements, and action item management |
| [**Roles & Personas**](octoacme-roles-and-personas.md) | Detailed role descriptions, responsibilities, goals, and communication patterns |

## Quick Start

**New to OctoAcme projects?**
- Start with [Overview](octoacme-project-management-overview.md) to understand our principles and roles
- Then read [Project Initiation](octoacme-project-initiation.md) if you're starting a new project
- Review [Roles & Personas](octoacme-roles-and-personas.md) to find your role and responsibilities

**Already running a project?**
- Check [Execution & Tracking](octoacme-execution-and-tracking.md) for day-to-day workflows
- Refer to [Risk Management & Communication](octoacme-risks-and-communication.md) for stakeholder updates
- Use [Release & Deployment](octoacme-release-and-deployment.md) when preparing to ship

**Wrapping up or retrospecting?**
- See [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) for running effective retrospectives

## Key Artifacts

Across all phases, we maintain these key artifacts (typically stored in the project repository):

- **Project Charter / One-pager** — Problem, goal, success metrics, stakeholders, timeline
- **Roadmap and Release Plan** — Milestones and delivery timeline
- **Sprint/Iteration Backlog** — Prioritized work with acceptance criteria and estimates
- **Risk Register** — ID, description, impact, likelihood, owner, mitigation, status
- **Definition of Done** — Team-agreed standards for completed work
- **Retrospective Notes** — Action items and continuous improvement tracking

## Communication & Support

If you have questions about these processes:
- Check the relevant process document first
- Reach out to your Project Manager or Product Manager
- Add your question as an issue in this repository to help improve documentation

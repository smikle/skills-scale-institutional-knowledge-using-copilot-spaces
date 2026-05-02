# OctoAcme Project Management Processes

## Overview

OctoAcme follows a structured, customer-first project management approach designed around iterative delivery and clear ownership. This documentation provides guidance for teams implementing OctoAcme project management practices across all cross-functional projects that deliver product features, services, or integrations.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

OctoAcme operates across five core lifecycle phases:

1. **Initiation** - Validate business needs, create Project One-pager, align stakeholders
2. **Planning** - Break work into shippable increments, map dependencies, establish timeline
3. **Execution** - Build, test, review, and iterate with daily standups and continuous quality checks
4. **Release** - Deploy to production with standardized checklists, smoke tests, and verification
5. **Close & Retrospective** - Capture learnings and convert them into actionable improvements

## Key Roles

- **Project Manager (PM)**: Coordinates delivery, manages schedules, risks, and communications
- **Product Manager (PdM)**: Defines outcomes, prioritizes backlog, measures success
- **Developers**: Implement features, collaborate on design and testability
- **QA/Testing**: Validates quality and acceptance criteria

## Communication Cadence

- **Daily**: 15-minute standups (progress, blockers, dependencies)
- **Weekly**: Delivery sync and PM + PdM alignment
- **Twice-weekly**: Team standups (or as agreed)
- **Monthly**: Stakeholder updates
- **Ad-hoc**: Risk escalations as needed

## Quality & Execution Standards

- Small PRs (≤400 lines when possible) with required approvals
- Multi-layer quality: unit tests, integration tests, E2E smoke tests, security scanning, manual QA
- GitHub Projects board with standardized workflow: Backlog → Ready → In Progress → In Review → QA → Done
- Weekly risk register reviews and velocity/burndown tracking

## Learning & Improvement

Teams conduct retrospectives (45–75 minutes) after each sprint, release, or milestone to:
- Identify what went well
- Capture opportunities for improvement
- Assign 2–3 prioritized action items with clear owners
- Measure and celebrate iterative improvements

## Process Documentation

This folder contains detailed guidance for each phase:
- [octoacme-project-management-overview.md](octoacme-project-management-overview.md) - High-level introduction
- [octoacme-project-initiation.md](octoacme-project-initiation.md) - Validation and authorization
- [octoacme-project-planning.md](octoacme-project-planning.md) - Actionable planning
- [octoacme-execution-and-tracking.md](octoacme-execution-and-tracking.md) - Day-to-day execution
- [octoacme-risks-and-communication.md](octoacme-risks-and-communication.md) - Risk and stakeholder management
- [octoacme-release-and-deployment.md](octoacme-release-and-deployment.md) - Release standardization
- [octoacme-retrospective-and-continuous-improvement.md](octoacme-retrospective-and-continuous-improvement.md) - Learning loops
- [octoacme-roles-and-personas.md](octoacme-roles-and-personas.md) - Role definitions

---

For questions or to propose updates to these processes, use the ["Add Content to Project Management Process Docs"](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) issue template.
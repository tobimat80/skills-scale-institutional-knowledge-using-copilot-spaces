# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation hub. This repository contains comprehensive guides and process documentation for running projects collaboratively and delivering customer value efficiently.

## Quick Overview

OctoAcme uses a structured, iterative approach to project management built on core principles of **customer focus**, **clear ownership**, and **data-informed decisions**. Our project lifecycle consists of five key phases: Initiation, Planning, Execution, Release, and Close & Retrospective.

### OctoAcme Project Management Approach

OctoAcme operates projects through a structured five-phase lifecycle that balances strategic planning with adaptive execution. The **Initiation phase** focuses on validating business need and creating a lightweight Project One-pager that captures the problem statement, measurable success metrics, stakeholder alignment, and resource requirements. Once approved by leadership, teams move into **Planning**, where work is broken into shippable increments with clear acceptance criteria, prioritized backlogs, and defined dependencies. This deliberate front-loading of clarity helps minimize scope creep and rework downstream.

During **Execution**, three core roles drive the work: **Project Managers** coordinate schedules, risks, and communications; **Product Managers** define outcomes, prioritize the backlog, and measure success; and **Developers** implement features, collaborate on design, and maintain quality standards. The organization emphasizes clear ownership and psychological safety, with communication structured around a predictable cadence: daily standups (15 min) for progress and blockers, weekly PM/PdM syncs, twice-weekly delivery team standups, and monthly stakeholder updates. Risk escalation follows a three-level model—team triage, PM escalation to Product Lead, and sponsor-level escalation for business-impacting issues.

Teams use GitHub Projects to track work through columns (Backlog → Ready → In Progress → In Review → QA → Done) and enforce quality gates including small PRs (≤400 lines), automated CI testing and security scanning, and at least one approval before merge. Testing is comprehensive: unit tests for new logic, integration tests where applicable, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. The **Release phase** standardizes deployment with pre-release requirements (passing CI, security scans, drafted release notes, and rollback plans), while the **Close & Retrospective phase** captures learnings and converts them into actionable improvements. This iterative, data-informed approach—measured through velocity, burndown, and success metrics from the Project One-pager—enables OctoAcme to deliver incrementally while maintaining psychological safety and continuous learning.

## Project Management Phases

1. **Initiation** — Validate business need, align stakeholders, and decide to proceed
2. **Planning** — Create actionable plans, estimate scope, and identify dependencies
3. **Execution** — Build, test, iterate, and track progress daily
4. **Release** — Deploy to production and verify success
5. **Close & Retrospective** — Capture learnings and improve

## Process Documentation

### Foundational Guides
- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for an introduction to OctoAcme's approach, core roles, and key artifacts
- **[Roles and Personas](octoacme-roles-and-personas.md)** — Definitions of Project Manager, Product Manager, Developer, and QA responsibilities

### Lifecycle Guides
- **[Project Initiation Guide](octoacme-project-initiation.md)** — Steps to validate and authorize work, align stakeholders, and create a lightweight plan
- **[Project Planning](octoacme-project-planning.md)** — Break work into shippable increments, identify risks, and align timelines
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day execution, team rhythm, quality standards, and reporting
- **[Release & Deployment Guide](octoacme-release-and-deployment.md)** — Standardize feature releases to production and manage rollbacks
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings and convert them into actionable improvements

### Supporting Guides
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify, manage, and communicate risks and dependencies; escalation paths

## Core Roles

- **Project Manager** — Coordinates delivery, schedules, risks, and communications
- **Product Manager** — Defines outcomes, prioritizes backlog, and measures success
- **Developers** — Implement features, collaborate on design, and maintain code quality
- **QA/Testing** — Validates quality and acceptance criteria

## How to Use These Docs

- **New to OctoAcme?** Start with [Project Management Overview](octoacme-project-management-overview.md)
- **Starting a new project?** Follow the sequence: Initiation → Planning → Execution → Release → Retrospective
- **Need guidance on a specific topic?** Use the process documentation index above to find the relevant guide
- **Contributing improvements?** See the contribution guidelines and use the "[Add Content to Project Management Process Docs](https://github.com/tobimat80/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)" issue template

## Getting Help

For questions about processes or to propose improvements, open an issue using the "[Add Content to Project Management Process Docs](https://github.com/tobimat80/skills-scale-institutional-knowledge-using-copilot-spaces/blob/main/.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)" template.

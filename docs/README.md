# OctoAcme Project Management Documentation

## Overview

OctoAcme follows a structured, customer-first project lifecycle that emphasizes iterative delivery, clear ownership, and data-informed decision-making. The approach consists of five core phases: **Initiation** (validating business need and stakeholder alignment through a Project One-pager), **Planning** (breaking work into shippable increments with prioritized backlogs and defined acceptance criteria), **Execution** (building and testing with daily standups and weekly delivery syncs), **Release** (deploying to production with pre-release verification and rollback plans), and **Close & Retrospective** (capturing learnings and continuous improvement). Throughout the lifecycle, the organization maintains a simple but powerful Risk Register to track, assess, and mitigate dependencies and blockers, ensuring transparency across teams.

The project governance model centers on three core roles with clear, interdependent responsibilities. **Product Managers** define what should be built by establishing problem statements, success metrics, and roadmap prioritization. **Project Managers** coordinate delivery, manage schedules, escalate risks, and facilitate communication across stakeholders. **Developers** implement features, maintain quality through testing and documentation, and collaborate on design and technical risk mitigation. This structure ensures that each project has named owners for outcomes (PdM), delivery (PM), and execution (development team), reducing ambiguity and enabling rapid decision-making.

Communication and risk management are woven throughout OctoAcme's execution model. The team maintains a regular cadence of **daily standups** (15 minutes, focused on blockers and dependencies), **weekly PM-PdM alignment**, **twice-weekly delivery standups**, and **monthly stakeholder updates**. Risks are escalated through a three-level path: team triage → PM escalation to Product Lead and dependent teams → sponsor-level escalation for business-impacting issues. The organization uses standardized templates for weekly status reporting, incident communication, and action item tracking, ensuring consistent, timely visibility across all stakeholder groups.

Quality and continuous improvement are embedded in every phase. OctoAcme requires small PRs (≤400 lines when possible) with automated CI/CD validation, unit and integration tests, security scanning, and peer approval before merging. Post-release, the team conducts structured retrospectives (45–75 minutes) to capture what went well, what could improve, and actionable next steps with named owners. This **continuous improvement culture**—measuring the impact of changes and celebrating iterative progress—helps the organization learn from each project and refine its processes systematically.

## Core Principles

- **Customer-first**: Prioritize customer value and usability
- **Iterative delivery**: Deliver small, testable increments
- **Clear ownership**: Each project has a named Project Manager (PM) and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback and learning

## Project Lifecycle

1. **Initiation** - Validate business need, align stakeholders, create lightweight plan
2. **Planning** - Break work into shippable increments, define scope and timeline
3. **Execution** - Build, test, review, and iterate with structured team rhythm
4. **Release** - Deploy to production with reduced risk and clear verification
5. **Close & Retrospective** - Capture learnings and drive continuous improvement

## Documentation Guide

### Getting Started

- **[Project Management Overview](./octoacme-project-management-overview.md)** - High-level introduction to OctoAcme roles, artifacts, and communication cadence
- **[Roles & Personas](./octoacme-roles-and-personas.md)** - Definitions of typical roles (PMs, Developers, QA) and their responsibilities

### Project Phases

- **[Project Initiation](./octoacme-project-initiation.md)** - Steps to validate and authorize work, align stakeholders, and create initial plans
- **[Project Planning](./octoacme-project-planning.md)** - Turning approved initiatives into actionable plans and backlog
- **[Execution & Tracking](./octoacme-execution-and-tracking.md)** - Day-to-day execution management, team rhythm, and progress tracking
- **[Release & Deployment](./octoacme-release-and-deployment.md)** - Standardized release process to reduce risk and improve observability

### Cross-cutting Topics

- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** - Identifying, managing, and communicating risks and dependencies
- **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** - Capturing learnings and converting them into actionable improvements

## How to Use These Docs

- **For new team members**: Start with the Overview and Roles docs, then follow the project lifecycle guides as you move through each phase
- **For ongoing projects**: Reference the relevant phase guide and cross-cutting topic docs as needed
- **In Copilot Spaces**: Add references to `.copilot/` for Copilot to use as context when assisting with project tasks

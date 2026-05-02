# OctoAcme Project Management Processes

## Overview

OctoAcme follows a customer-first, iterative delivery model built around clear ownership and data-informed decisions. The organization organizes work through a structured lifecycle: initiation (validating business need and stakeholder alignment), planning (breaking work into shippable increments with defined acceptance criteria), execution (daily standups and continuous tracking), release (standardized deployment with risk mitigation), and retrospectives for continuous improvement. Each project has a Project Manager who coordinates delivery and communications, alongside a Product Manager who defines outcomes and prioritizes the backlog. This dual-leadership structure ensures both business alignment and operational execution, supported by developers, QA specialists, and stakeholders who contribute through clearly defined roles and responsibilities.

## Core Roles and Personas

OctoAcme defines three core personas that drive project execution:

- **Developers** - Implement features while maintaining code quality and identifying technical risks. They participate in daily standups and code reviews.
- **Product Managers** - Define the product vision, prioritize based on customer value, and measure success through metrics. They align weekly with project leads.
- **Project Managers** - Manage schedules, dependencies, and stakeholder communication. They maintain status updates and risk registers.

This role clarity prevents confusion and ensures accountability across the project lifecycle, from inception through retrospectives.

## Communication Strategy

Communication is structured through a regular cadence that maintains alignment without creating excessive overhead:

- **Weekly Syncs** - Between PM and Product Manager to align on progress and risks
- **Twice-Weekly Standups** - Keep the delivery team coordinated on blockers and dependencies
- **Monthly Stakeholder Updates** - Provide visibility to wider audiences
- **Status Template** - Progress, next steps, risks/blockers, and decisions needed
- **Escalation Paths** - Team → PM → Product Lead → Sponsor, with separate protocols for critical incidents

A blameless post-mortem approach ensures learning from incidents while maintaining team psychological safety.

## Quality Assurance Practices

Quality assurance is embedded throughout OctoAcme's execution model rather than gated at the end:

- **Automated Testing & Linting** - Enforced in CI pipelines
- **Code Review Requirements** - Small pull requests (≤400 lines) with at least one approval
- **Security Scanning** - Performed before release
- **Testing Layers** - Unit tests for new logic, integration tests for dependencies, end-to-end smoke tests for critical flows
- **Definition of Done** - Documented to ensure consistency across projects
- **Incident Response** - Rollback and incident playbooks reduce risk
- **Continuous Improvement** - Retrospectives after each sprint or release focus on 2–3 prioritized action items that feed into future planning

## Project Lifecycle

OctoAcme's structured approach spans five key phases:

1. **Initiation** - Validate business need, identify stakeholders, define success metrics
2. **Planning** - Break work into shippable increments with acceptance criteria and risk identification
3. **Execution** - Daily standups, continuous tracking, PR reviews, and iterative delivery
4. **Release** - Standardized deployment with pre-release requirements and rollback plans
5. **Retrospectives** - Capture learnings and convert them into actionable improvements

For detailed guidance on each phase, refer to the process-specific documentation in this folder.

# OctoAcme Project Management

Welcome to OctoAcme's centralized project management documentation. This README provides an overview of our project management philosophy, approach, and key processes to help new teammates quickly understand how we work and where to find detailed guidance.

## Our Philosophy

At OctoAcme, we believe in building software that delivers real value to our customers through collaboration, transparency, and continuous improvement. Our project management approach is guided by these core principles:

### Core Principles

- **Customer-first**: We prioritize customer value and usability in every decision
- **Iterative delivery**: We deliver small, testable increments to get feedback early and often
- **Clear ownership**: Each project has a named Project Manager and Product Lead with defined responsibilities
- **Data-informed decisions**: We measure impact and iterate based on evidence, not assumptions
- **Psychological safety**: We encourage feedback, learning, and blameless retrospectives to foster continuous improvement

## Project Lifecycle

OctoAcme projects follow a structured lifecycle with five key stages:

### 1. Initiation
Define and validate the project idea, align stakeholders, and create a lightweight plan. This stage confirms the business need, identifies stakeholders, and establishes success criteria.

**Key Outputs**: Project One-pager, Stakeholder list, High-level timeline, Initial risk assessment

### 2. Planning
Turn the approved initiative into an actionable plan and backlog for delivery. Break work into shippable increments, identify dependencies, and define the Definition of Done.

**Key Outputs**: Prioritized backlog, Release plan, Risk register, Definition of Done

### 3. Execution
Manage day-to-day development activities and track progress toward milestones. Follow established workflows, maintain quality standards, and escalate blockers when needed.

**Key Outputs**: Working software, Test coverage, Progress reports, Updated risk register

### 4. Release
Deploy features to production following standardized processes to reduce risk and improve observability. Ensure all acceptance criteria are met and rollback plans are in place.

**Key Outputs**: Deployed features, Release notes, Post-deployment verification, Stakeholder announcements

### 5. Retrospective
Capture learnings and convert them into actionable improvements. Reflect on what went well, what could be improved, and establish action items with clear owners.

**Key Outputs**: Retrospective notes, Action items, Process improvements

## Roles and Responsibilities

### Project Manager (PM)
Coordinates delivery activities, manages schedules, risks, and communications. Facilitates meetings and ensures project documentation is up-to-date.

**Key Focus**: On-time delivery, transparency, stakeholder alignment

### Product Manager (PdM)
Defines what should be built to deliver customer and business value. Owns the product vision, prioritizes the backlog, and measures outcomes.

**Key Focus**: Customer value, data-driven prioritization, product-market fit

### Developers
Design, build, test, and deliver software components that meet acceptance criteria and quality standards. Participate in design reviews and help identify technical risks.

**Key Focus**: Reliable and maintainable code, high test coverage, reduced cycle time

### QA Tester
Validates quality and acceptance criteria through manual and automated testing. Ensures features meet requirements before release.

**Key Focus**: Quality assurance, test coverage, acceptance validation

### Stakeholders
Provide inputs, approvals, and feedback throughout the project lifecycle.

**Key Focus**: Strategic alignment, resource allocation, decision-making

## Communication Rhythms

Regular communication ensures alignment and helps identify blockers early:

- **Daily Standups** (15 min): Team-level sync on progress, blockers, and dependencies
- **Weekly Syncs**: PM + PdM alignment; delivery team sync on progress and risks
- **Sprint/Iteration Reviews**: Demo completed work at the end of each sprint or milestone
- **Monthly Stakeholder Updates**: High-level progress reports for broader stakeholders
- **Retrospectives**: After each sprint, release, or milestone to capture learnings
- **Ad-hoc Escalations**: As needed for urgent issues or blockers

## Quality Assurance

Quality is built into every stage of our process:

### Automated Pipelines
- Continuous Integration (CI) runs automated tests and linting on every pull request
- Security scanning integrated into CI pipelines
- Automated deployment to staging and production environments

### Testing Coverage
- **Unit tests** for new logic and business rules
- **Integration tests** for component interactions
- **End-to-end smoke tests** for critical user flows before release
- **Manual QA** for feature acceptance when needed

### Definition of Done (DoD)
Every team defines and adheres to a Definition of Done that typically includes:
- All acceptance criteria met
- Code reviewed and approved
- Tests written and passing
- Documentation updated
- Security scans passing
- Deployed to staging and verified

## Key Artifacts

Throughout the project lifecycle, we maintain these important documents:

- **Project Charter / One-pager**: Problem statement, goals, success metrics
- **Roadmap and Release Plan**: Timeline, milestones, and deliverables
- **Sprint/Iteration Backlog**: Prioritized work items with acceptance criteria
- **Acceptance Criteria & Definition of Done**: Clear requirements for completion
- **Risk Register**: Identified risks with mitigation plans and status
- **Retrospective Notes**: Learnings and action items for improvement

## Process Documentation

For detailed guidance on each stage and aspect of our project management approach, refer to these documents:

### Overview and Principles
- [Project Management Overview](./octoacme-project-management-overview.md) - High-level introduction to OctoAcme's approach

### Lifecycle Stage Guides
- [Project Initiation](./octoacme-project-initiation.md) - How to validate and authorize new projects
- [Project Planning](./octoacme-project-planning.md) - Creating actionable plans and backlogs
- [Execution and Tracking](./octoacme-execution-and-tracking.md) - Day-to-day execution and progress tracking
- [Release and Deployment](./octoacme-release-and-deployment.md) - Standardized release processes
- [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Learning and improving

### Cross-Cutting Practices
- [Roles and Personas](./octoacme-roles-and-personas.md) - Detailed role definitions and responsibilities
- [Risk Management & Communication](./octoacme-risks-and-communication.md) - Risk identification and stakeholder communication

## Getting Started

**New to OctoAcme?** Start here:
1. Read this README to understand our philosophy and approach
2. Review the [Project Management Overview](./octoacme-project-management-overview.md) for more context
3. Explore the [Roles and Personas](./octoacme-roles-and-personas.md) guide to understand your role
4. Dive into specific lifecycle guides as needed for your current project stage

**Starting a new project?** Follow this path:
1. [Project Initiation](./octoacme-project-initiation.md) - Create your project one-pager
2. [Project Planning](./octoacme-project-planning.md) - Build your backlog and release plan
3. [Execution and Tracking](./octoacme-execution-and-tracking.md) - Execute with quality
4. [Release and Deployment](./octoacme-release-and-deployment.md) - Ship to production
5. [Retrospective and Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) - Learn and improve

## Using with Copilot Spaces

To make this documentation available in Copilot Spaces:
- Add process-specific docs to `.copilot/` directory in your project repository
- Reference this README and related documents in your Copilot Space configuration
- Use role-specific personas from the Roles and Personas guide to shape context-aware guidance

## Questions or Feedback?

We continuously improve our processes based on team feedback. If you have suggestions or questions:
- Open an issue in the project repository
- Bring it up in your team's retrospective
- Discuss with your Project Manager or Product Manager

---

*Related to: [Issue #2](https://github.com/kodehaus/skills-scale-institutional-knowledge-using-copilot-spaces/issues/2)*

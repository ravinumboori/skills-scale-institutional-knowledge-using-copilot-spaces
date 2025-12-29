# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Product Owner

### Role Summary
Product Owners prioritize and own the product backlog, clarify requirements, and act as the voice of the customer. They bridge the gap between stakeholders and the delivery team to ensure the right features are built.

### Responsibilities
- Own and prioritize the product backlog
- Define and refine user stories with clear acceptance criteria
- Clarify requirements and make scope decisions
- Validate solutions and accept deliverables
- Maintain feedback cycle with customers and stakeholders
- Balance business value, technical feasibility, and user needs

### Goals
- Maximize product value delivered to customers
- Ensure backlog items are clear, actionable, and prioritized
- Maintain alignment between business needs and development work
- Enable the team to deliver with minimal rework

### Typical Communication
- Daily collaboration with delivery team during standups
- Regular backlog grooming and prioritization sessions
- Sprint planning and review participation
- Stakeholder updates on feature delivery and roadmap

### Interactions with Other Roles
- **Project Manager**: Collaborates on planning, timeline commitments, and risk management
- **Product Manager**: Aligns on product vision and strategic priorities
- **Developers**: Provides clarification on requirements and acceptance criteria
- **QA Lead**: Reviews test plans and validates release readiness
- **Stakeholder Representative**: Gathers requirements and demonstrates progress

---

## QA Lead

### Role Summary
QA Leads oversee the quality assurance process, define test strategies, coordinate testing activities, and advocate for quality standards throughout the project lifecycle.

### Responsibilities
- Define and maintain test strategy and plans
- Coordinate testing activities across the team
- Set and enforce quality standards and acceptance criteria
- Identify quality risks and recommend mitigations
- Lead test automation efforts
- Perform or delegate acceptance testing
- Report on quality metrics and test coverage

### Goals
- Ensure releases meet quality standards before deployment
- Minimize production defects and customer-reported issues
- Improve test coverage and automation
- Build a quality-first culture within the team

### Typical Communication
- Daily standup participation and blocker reporting
- Test status updates in weekly delivery syncs
- Quality gate reviews before releases
- Defect triage meetings with developers

### Interactions with Other Roles
- **Project Manager**: Reports on quality risks and testing progress
- **Product Owner**: Validates acceptance criteria and participates in release decisions
- **Developers**: Collaborates on test automation, reviews PRs for testability
- **UX Designer**: Tests user flows and validates usability standards
- **Stakeholder Representative**: Demonstrates quality and addresses concerns

---

## UX Designer

### Role Summary
UX Designers create user-centered designs, gather user feedback, ensure usability standards, and develop wireframes and prototypes that guide feature implementation.

### Responsibilities
- Design user interfaces and user experiences
- Create wireframes, mockups, and prototypes
- Conduct user research and usability testing
- Define interaction patterns and design guidelines
- Ensure accessibility and usability standards
- Collaborate on design system components
- Validate implemented features meet design intent

### Goals
- Deliver intuitive, accessible user experiences
- Reduce user friction and improve satisfaction
- Establish and maintain design consistency
- Advocate for user needs throughout development

### Typical Communication
- Design reviews and feedback sessions
- Collaboration sessions with Product Owner and Developers
- Usability testing reports and recommendations
- Design handoff documentation

### Interactions with Other Roles
- **Product Owner**: Collaborates on requirements and validates design solutions
- **Product Manager**: Aligns design with product vision and strategy
- **Developers**: Provides design specifications and supports implementation
- **QA Lead**: Partners on usability testing and validation
- **Stakeholder Representative**: Presents designs and gathers feedback

---

## Stakeholder Representative

### Role Summary
Stakeholder Representatives provide business requirements, review project progress, accept deliverables, and ensure the project aligns with organizational objectives and stakeholder expectations.

### Responsibilities
- Articulate business needs and requirements
- Review and approve project deliverables
- Provide timely feedback on progress and direction
- Escalate business risks and concerns
- Participate in key project ceremonies (kickoffs, reviews, retrospectives)
- Advocate for user and business needs
- Support change management and adoption

### Goals
- Ensure project outcomes align with business objectives
- Provide clear guidance and timely decisions
- Minimize scope creep and misalignment
- Support successful adoption of deliverables

### Typical Communication
- Weekly or bi-weekly status reviews with Project Manager
- Milestone reviews and release acceptance
- Escalation of business-critical issues
- Retrospective participation for continuous improvement

### Interactions with Other Roles
- **Project Manager**: Primary point of contact for status, decisions, and escalations
- **Product Owner**: Provides business requirements and feedback on priorities
- **Product Manager**: Aligns on strategic direction and success metrics
- **QA Lead**: Reviews quality standards and acceptance criteria
- **Developers**: Provides domain expertise and clarifications as needed

---

## Role Collaboration Overview

The following table shows how these roles interact during typical project activities:

| Activity | Primary Roles | Supporting Roles | Consulted/Informed |
|----------|---------------|------------------|--------------------|
| Project Initiation | Project Manager, Product Owner | Stakeholder Representative | All team members |
| Requirements Definition | Product Owner, UX Designer | Product Manager, Stakeholder Representative | Developers, QA Lead |
| Sprint Planning | Project Manager, Product Owner, Developers | QA Lead, UX Designer | Stakeholder Representative |
| Daily Execution | Developers, QA Lead | UX Designer | Project Manager, Product Owner |
| Code Review | Developers | QA Lead | UX Designer (for UI changes) |
| Testing & QA | QA Lead, Developers | Product Owner | Project Manager |
| Design Reviews | UX Designer, Product Owner | Developers, QA Lead | Stakeholder Representative |
| Release Decision | Product Owner, QA Lead, Project Manager | Stakeholder Representative | All team members |
| Retrospectives | All team members | Project Manager (facilitator) | Stakeholder Representative (optional) |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The expanded role set provides better coverage of modern cross-functional project teams.
- Reference the Role Collaboration Overview to understand accountability across project phases.


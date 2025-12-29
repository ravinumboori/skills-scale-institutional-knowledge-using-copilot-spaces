# OctoAcme RACI Quick Reference

## Purpose
This document provides a RACI (Responsible, Accountable, Consulted, Informed) matrix for key activities across the OctoAcme project lifecycle. Use this to clarify accountability and reduce confusion about who does what.

## RACI Key
- **R** (Responsible): Does the work to complete the task
- **A** (Accountable): Ultimately answerable for completion and has approval authority (only one A per activity)
- **C** (Consulted): Provides input and expertise (two-way communication)
- **I** (Informed): Kept up-to-date on progress (one-way communication)

---

## Project Initiation Phase

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Create Project One-pager | R | C | A | I | C | I | C |
| Define Success Metrics | C | R | A | I | C | I | C |
| Identify Stakeholders | R | C | C | I | I | I | A |
| Initial Risk Assessment | A/R | C | C | C | C | C | C |
| Resource Planning | A/R | C | C | I | I | C | C |
| Go/No-Go Decision | C | C | C | I | I | I | A |

---

## Planning Phase

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Project Kickoff | A/R | R | C | R | R | R | C |
| Backlog Creation | C | A/R | C | I | C | C | I |
| Backlog Prioritization | C | A/R | C | I | C | C | C |
| Sprint Planning | R | A | I | C | C | R | I |
| Define DoD | C | C | I | A/R | C | C | I |
| Test Strategy | C | C | I | A/R | I | C | I |
| Design Planning | C | C | C | I | A/R | C | C |
| Estimate Effort | R | C | I | C | C | A | I |
| Create Release Plan | A/R | C | C | C | I | C | C |

---

## Execution Phase

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Daily Standup | R | C | I | R | R | A/R | I |
| Feature Development | C | C | I | I | C | A/R | I |
| Code Review | I | I | I | C | C | A/R | I |
| Design Implementation | C | C | I | I | A | R | I |
| Unit Testing | I | I | I | C | I | A/R | I |
| Integration Testing | C | C | I | A/R | I | R | I |
| Usability Testing | C | C | I | C | A/R | I | I |
| Bug Triage | C | C | I | A/R | I | R | I |
| Progress Tracking | A/R | C | I | C | I | C | I |
| Risk Management | A/R | C | C | C | C | C | C |
| Weekly Status Update | A/R | C | I | C | I | C | I |

---

## Quality Assurance

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Define Test Cases | I | C | I | A/R | C | C | I |
| Execute Test Plan | C | I | I | A/R | I | R | I |
| Acceptance Testing | C | A | I | R | C | R | I |
| Performance Testing | C | C | I | A/R | I | R | I |
| Security Testing | C | C | I | A/R | I | R | I |
| Quality Gate Review | C | A | I | R | I | C | C |

---

## Release & Deployment

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Release Planning | A/R | C | C | C | I | C | C |
| Pre-release QA Sign-off | C | C | I | A | I | C | I |
| Product Owner Acceptance | C | A | I | C | I | C | C |
| Release Notes | R | C | I | C | C | C | I |
| Deployment Execution | C | I | I | C | I | A/R | I |
| Smoke Testing | C | C | I | A/R | I | R | I |
| Release Communication | A/R | C | I | I | I | I | I |
| Stakeholder Acceptance | C | C | I | I | I | I | A |

---

## Communication & Escalation

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Status Reporting | A/R | C | I | C | I | C | I |
| Stakeholder Updates | A/R | C | I | I | I | I | C |
| Risk Escalation | A/R | C | C | C | C | C | C |
| Blocker Resolution | A | C | C | R | R | R | C |
| Change Requests | C | C | C | C | C | C | A |

---

## Retrospective & Continuous Improvement

| Activity | Project Manager | Product Owner | Product Manager | QA Lead | UX Designer | Developers | Stakeholder Rep |
|----------|----------------|---------------|-----------------|---------|-------------|------------|-----------------|
| Facilitate Retrospective | A/R | R | I | R | R | R | C |
| Identify Improvements | C | R | I | R | R | R | C |
| Action Item Ownership | C | R | I | R | R | R | I |
| Track Improvements | A/R | C | I | C | C | C | I |
| Measure Impact | R | A | C | C | C | C | C |

---

## Notes and Best Practices

### Using This Matrix
1. **Reference before starting activities**: Check who should be involved and how
2. **Clarify early**: If roles are unclear, discuss and document decisions
3. **Adapt as needed**: Not every project needs every role; scale to project size
4. **Avoid too many As**: Each activity should have only one Accountable person
5. **Don't overcommunicate**: Too many Cs and Is can slow down work

### Common Patterns
- **Project Manager** is typically Accountable for process and coordination
- **Product Owner** is typically Accountable for scope and acceptance decisions
- **QA Lead** is typically Accountable for quality standards and testing
- **UX Designer** is typically Accountable for design and usability
- **Developers** are typically Accountable for implementation quality
- **Stakeholder Representative** is typically Accountable for business acceptance

### When Conflicts Arise
- If multiple people believe they are Accountable for the same activity, escalate to Product Manager or sponsor
- Document the decision and update this matrix for future reference
- Communicate the clarification to all team members

### Related Documents
- [octoacme-roles-and-personas.md](./octoacme-roles-and-personas.md) - Detailed role descriptions
- [octoacme-project-management-overview.md](./octoacme-project-management-overview.md) - High-level process overview

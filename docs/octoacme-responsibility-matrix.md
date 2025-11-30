# OctoAcme Responsibility Matrix (RACI)

## Purpose
This document provides a clear accountability framework using the RACI model (Responsible, Accountable, Consulted, Informed) for key project management activities across all OctoAcme roles.

## RACI Model Definitions

- **R (Responsible)**: The role(s) that perform the work to complete the task
- **A (Accountable)**: The role with ultimate accountability for the task's completion (only one A per task)
- **C (Consulted)**: Roles whose input is sought before decisions or actions
- **I (Informed)**: Roles who are kept informed of progress or decisions

## Project Lifecycle RACI Matrix

### Initiation Phase

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Create Project One-pager | R | A | I | C | I | I | C | I |
| Identify Stakeholders | C | R | I | C | I | A | I | I |
| Define Success Metrics | C | A | C | R | I | I | I | I |
| Initial Risk Assessment | R | C | C | I | I | I | A | I |
| Approve Project Go/No-Go | I | C | I | A | I | I | I | I |

### Planning Phase

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Create Project Plan | A | C | C | I | I | I | R | I |
| Define Scope & Backlog | R | A | C | C | I | I | C | I |
| Resource Allocation | A | C | I | C | I | I | I | I |
| Establish Communication Plan | R | I | I | C | I | A | I | I |
| Risk Register Setup | R | C | C | I | I | C | A | I |
| Process Documentation | C | I | I | I | A | I | I | R |

### Execution Phase

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Implement Features | I | C | A | I | I | I | I | I |
| Daily Standups | R | I | R | I | I | C | I | I |
| Code Reviews | I | I | A/R | I | C | I | I | I |
| Sprint Planning | R | A | R | I | C | I | C | I |
| Status Reporting | R | C | I | I | I | A | R | I |
| Risk Monitoring | R | C | C | I | I | C | A | I |
| Manage Blockers | A | C | R | C | I | R | R | I |
| Quality Assurance | R | C | A | I | C | I | C | I |

### Release & Deployment

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Release Planning | R | A | R | C | I | C | C | C |
| Deployment Execution | R | C | A | I | I | I | R | I |
| Release Communications | C | C | I | I | I | A | I | I |
| Stakeholder Sign-off | R | C | I | A | I | C | I | I |
| Post-Deployment Verification | R | C | A | I | C | I | R | I |

### Close & Retrospective

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Facilitate Retrospective | A | R | R | C | C | C | R | R |
| Document Lessons Learned | R | C | C | I | A | I | C | C |
| Process Improvement Actions | C | C | C | I | A | I | I | R |
| Final Status Report | A | R | I | I | I | R | C | I |
| Archive Project Documentation | R | I | I | I | A | I | I | I |

## Ongoing Activities

| Activity | Project Manager | Product Manager | Developer | Stakeholder | Process Owner | Communication Lead | Risk Manager | Change Champion |
|----------|----------------|-----------------|-----------|-------------|---------------|-------------------|--------------|-----------------|
| Process Documentation Maintenance | I | I | C | I | A | I | I | R |
| Communication Channel Management | C | I | I | C | I | A | I | I |
| Risk Register Updates | R | C | C | I | I | C | A | I |
| Team Training & Onboarding | C | C | C | I | R | C | I | A |
| Stakeholder Engagement | R | R | I | C | I | A | I | I |
| Change Management Initiatives | C | C | C | I | C | I | I | A |

## How to Use This Matrix

1. **Reference during project kickoff** to clarify roles and expectations
2. **Use when unclear about ownership** of a specific task or decision
3. **Review during role transitions** to ensure smooth handoffs
4. **Update as needed** when new activities or roles are introduced
5. **Resolve conflicts** by ensuring only one 'A' (Accountable) per activity
6. **Onboard new team members** by showing them their responsibilities

## Important Notes

- **Single Point of Accountability**: Each activity should have exactly one 'A' (Accountable) role
- **Flexibility**: This matrix can be adapted based on team size and project complexity
- **Small Teams**: In smaller teams, one person may fulfill multiple roles
- **Escalation**: When unclear, escalate to the Accountable role for that activity
- **Regular Review**: Review and update this matrix quarterly or when significant process changes occur

## Related Documentation

- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Project Management Overview](octoacme-project-management-overview.md) - Process overview
- [Role Onboarding Checklist](octoacme-role-onboarding-checklist.md) - New role onboarding guide

---

*This responsibility matrix helps prevent gaps in accountability and ensures clear ownership across all project activities.*

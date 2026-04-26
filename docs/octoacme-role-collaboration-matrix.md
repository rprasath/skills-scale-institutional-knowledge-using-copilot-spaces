# OctoAcme Role Collaboration Matrix

This document provides a quick reference for understanding how different roles collaborate throughout the project lifecycle.

## Collaboration by Phase

### Initiation Phase
| Primary Role | Key Collaborators | Activity |
|---|---|---|
| Product Manager | Stakeholders, Project Manager, Business Analyst | Define problem, success metrics, business case |
| Project Manager | Product Manager, Stakeholders | Create charter, identify team, timeline |
| Business Analyst | Stakeholders, Product Manager | Gather initial requirements, validate scope |
| Scrum Master | Project Manager | Plan team structure and ceremonies |

### Planning Phase
| Primary Role | Key Collaborators | Activity |
|---|---|---|
| Product Manager | Developers, UX Designer, Business Analyst | Refine requirements, prioritize backlog |
| Project Manager | All roles | Create detailed plan, dependencies, milestones |
| Business Analyst | Developers, QA/Testing, UX Designer | Finalize acceptance criteria and specs |
| UX Designer | Product Manager, Developers | Create design specifications |
| Scrum Master | All roles | Facilitate planning meetings, confirm capacity |
| Developers | Product Manager, UX Designer, Business Analyst | Estimate work, identify technical risks |

### Execution Phase
| Primary Role | Key Collaborators | Activity |
|---|---|---|
| Developers | UX Designer, QA/Testing, Scrum Master | Build features, participate in standups |
| Scrum Master | All roles | Run ceremonies, remove impediments |
| QA/Testing | Developers, Business Analyst, Product Manager | Test, report defects, validate acceptance |
| UX Designer | Developers, QA/Testing | Review implementation, conduct usability testing |
| Project Manager | All roles | Track progress, manage risks, communicate status |
| Business Analyst | Developers, QA/Testing | Clarify requirements, support acceptance testing |

### Release & Deployment Phase
| Primary Role | Key Collaborators | Activity |
|---|---|---|
| Release Manager | Developers, QA/Testing, Project Manager, Operations | Coordinate deployment, communication |
| QA/Testing | Release Manager, Developers | Final verification, smoke tests |
| Project Manager | Release Manager, Stakeholders | Confirm readiness, communicate timeline |
| Product Manager | Release Manager, Stakeholders | Validate feature set, approve release |

### Retrospective & Improvement Phase
| Primary Role | Key Collaborators | Activity |
|---|---|---|
| Scrum Master | All roles | Facilitate retro, capture improvements |
| Project Manager | All roles | Analyze metrics, document lessons learned |
| Product Manager | Team | Assess impact of delivered features |

## Daily Interactions

### Standups
- **Participants**: Developers, Scrum Master, QA/Testing, Business Analyst
- **Led by**: Scrum Master
- **Purpose**: Progress update, blocker identification, dependency coordination

### Weekly Syncs
- **Project Manager + Product Manager**: Prioritization, risks, stakeholder updates
- **Development Team + Scrum Master**: Process health, velocity, capacity planning
- **QA/Testing + Developers**: Quality metrics, test coverage, defect trends

### Design Reviews
- **Participants**: UX Designer, Developers, Product Manager, QA/Testing
- **Purpose**: Validate design specifications, implementation feasibility, acceptance criteria

### Requirements Refinement
- **Participants**: Product Manager, Business Analyst, Developers, QA/Testing
- **Purpose**: Clarify stories, define acceptance criteria, estimate effort

## Decision Authority by Topic

| Decision | Authority | Consulted | Informed |
|---|---|---|---|
| Business Priority | Product Manager | Stakeholders | Team |
| Technical Approach | Developers | Architects, QA/Testing | Product Manager, Project Manager |
| User Experience | UX Designer | Product Manager | Developers, QA/Testing |
| Acceptance Criteria | Business Analyst | Product Manager, QA/Testing | Developers |
| Release Timing | Release Manager + Project Manager | Product Manager, Developers, QA/Testing | Stakeholders |
| Process Changes | Scrum Master | Team | Project Manager |
| Scope Changes | Project Manager | Product Manager, Stakeholders | Team |

## Key Handoff Points

1. **Planning → Execution**: Business Analyst & Developers → Acceptance criteria finalized; Developers ready to build
2. **Execution → QA**: Developers → Feature complete, PR merged; QA begins testing
3. **QA → Release**: QA/Testing → All criteria met, signed off; Release Manager schedules deployment
4. **Release → Support**: Release Manager + Product Manager → Feature live; Support notified, metrics tracked

## Escalation Path

For blockers or decisions:
1. **Team level** → Scrum Master works to resolve
2. **Cross-team dependencies** → Project Manager escalates
3. **Business/strategic decisions** → Product Manager + Stakeholders
4. **Sponsor-level issues** → Project Manager escalates to Sponsor

---

**When to use this matrix**: Reference this during planning, kickoffs, and when onboarding new team members to clarify roles and responsibilities.

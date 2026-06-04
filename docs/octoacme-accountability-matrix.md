# OctoAcme Accountability Matrix (RACI)

## Purpose
Define who is **Responsible**, **Accountable**, **Consulted**, and **Informed** (RACI) for key project activities. This prevents duplication, confusion, and gaps in ownership.

## Key Project Activities

### Project Initiation

| Activity | Product Manager | Project Manager | Business Analyst | Stakeholders | Sponsor |
|---|:---:|:---:|:---:|:---:|:---:|
| Define problem statement | **A/R** | C | R | C | I |
| Identify stakeholders | **A** | **R** | C | C | C |
| Create One-pager | R | **A/R** | R | C | C |
| Get sponsor approval | C | **A** | I | C | **A/R** |

**Legend:** A = Accountable (final decision) | R = Responsible (executes) | C = Consulted | I = Informed

### Backlog & Requirements

| Activity | Product Manager | Business Analyst | Developers | QA/Tester | Project Manager |
|---|:---:|:---:|:---:|:---:|:---:|
| Write user stories | **A** | **R** | C | C | I |
| Define acceptance criteria | **A** | **R** | C | R | I |
| Estimate complexity | I | C | **R** | C | **A** |
| Mark dependencies | I | I | **R** | I | **A** |
| Prioritize backlog | **A/R** | I | C | C | C |

### Design & Planning

| Activity | UX/UI Designer | Developers | Business Analyst | Project Manager | Product Manager |
|---|:---:|:---:|:---:|:---:|:---:|
| Create wireframes | **A/R** | C | C | I | C |
| Define design system | **A/R** | C | I | I | I |
| Technical design review | I | **A/R** | C | C | C |
| Build release plan | I | C | C | **A/R** | **A** |

### Development & Testing

| Activity | Developers | QA/Tester | UX/UI Designer | Technical Writer | Project Manager |
|---|:---:|:---:|:---:|:---:|:---:|
| Implement feature | **A/R** | I | C | I | I |
| Write unit tests | **A/R** | I | I | I | I |
| Execute test plan | I | **A/R** | C | I | I |
| Verify acceptance criteria | C | **A/R** | I | I | I |
| Document changes | R | I | I | **A** | I |
| Code review | **A** | I | C | I | I |

### Release & Deployment

| Activity | Release Manager | Developers | QA/Tester | Technical Writer | Project Manager |
|---|:---:|:---:|:---:|:---:|:---:|
| Pre-flight checklist | **A/R** | C | C | C | I |
| Smoke testing | C | C | **A/R** | I | I |
| Deploy to production | **A** | **R** | C | I | C |
| Publish release notes | C | C | I | **A/R** | I |
| Announce release | C | I | I | C | **A/R** |
| Monitor post-deploy | **A** | C | I | I | C |

### Retrospective & Closure

| Activity | Project Manager | All Team Members | Product Manager | Sponsor |
|---|:---:|:---:|:---:|:---:|
| Facilitate retro | **A/R** | C | I | I |
| Document action items | **A** | **R** | C | I |
| Capture metrics | **A/R** | C | C | C |
| Plan improvements | I | **R** | **A** | I |

## How to Use the RACI Matrix

1. **At project kickoff:** Review the RACI matrix with the team to clarify roles.
2. **When planning activities:** Assign roles explicitly using the RACI framework.
3. **During execution:** Refer to the matrix when questions arise about who decides or who acts.
4. **In retrospectives:** Identify activities where RACI was unclear and refine.

## Tips for Effective RACI

- **One accountable per activity:** Avoid multiple "A" entries unless co-leads are explicitly agreed.
- **Be specific:** Apply RACI to both phases and individual deliverables.
- **Update as needed:** Adjust RACI if team structure or process changes.
- **Communicate clearly:** Make RACI visible in project documentation and discuss in kickoff meetings.
- **Don't over-consult:** Limit "C" entries to roles that truly need input; use "I" for visibility only.

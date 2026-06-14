# OctoAcme Role Interaction Guide

## Purpose
Provide guidance on how roles interact, collaborate, and hand off work throughout the project lifecycle. This document helps teams clarify responsibilities at each stage and minimize confusion about ownership.

## Key Interaction Patterns

### Initiation Phase
**Primary roles:** Product Manager, Project Manager, Business Analyst, Stakeholders

- **Product Manager** articulates the business need and success metrics
- **Business Analyst** gathers stakeholder requirements and clarifies scope
- **Project Manager** creates the project charter and stakeholder communication plan
- **Output:** Project One-pager, stakeholder alignment, decision to proceed

### Planning Phase
**Primary roles:** Product Manager, Project Manager, Business Analyst, Developers, UX/UI Designer

- **Business Analyst** refines requirements into user stories with acceptance criteria
- **UX/UI Designer** creates wireframes and design specifications
- **Developers** estimate complexity and identify technical risks
- **Project Manager** builds the timeline and coordinates dependencies
- **Output:** Prioritized backlog, release plan, design specs, risk register

### Execution Phase
**Primary roles:** Developers, UX/UI Designer, QA/Tester, Technical Writer

- **Developers** implement features and request design and QA reviews
- **UX/UI Designer** validates implementation against design specifications
- **QA/Tester** confirms acceptance criteria and tests for quality
- **Technical Writer** documents changes and updates help content
- **Output:** Completed features, test reports, documentation updates

### Release Phase
**Primary roles:** Release Manager, QA/Tester, Developers, Technical Writer

- **QA/Tester** performs final smoke tests and confirms readiness
- **Release Manager** coordinates deployment and stakeholder communication
- **Developers** are on-call for rollback or critical fixes
- **Technical Writer** publishes release notes and feature announcements
- **Output:** Deployed release, release notes, stakeholder communication

### Retrospective Phase
**Primary roles:** Project Manager, all delivery team roles

- **Project Manager** facilitates the retrospective
- **All roles** contribute observations and action items
- **Output:** Action items, process improvements, metrics summary

## Handoff Checklist by Phase

### Initiation → Planning
- [ ] One-pager approved by stakeholders and Product Lead
- [ ] Business Analyst has gathered initial requirements
- [ ] Resource availability confirmed
- [ ] Risk register initiated

### Planning → Execution
- [ ] Backlog refined and prioritized
- [ ] Design specifications ready for implementation
- [ ] Developers have reviewed and estimated stories
- [ ] Test plan drafted by QA
- [ ] Definition of Done documented

### Execution → Release
- [ ] All acceptance criteria met and verified by QA
- [ ] Code reviewed and merged
- [ ] Documentation complete (user guides, release notes)
- [ ] Smoke test plan prepared and validated in staging
- [ ] Rollback plan documented

### Release → Operations
- [ ] Release deployed and verified in production
- [ ] Stakeholders notified
- [ ] Known issues documented
- [ ] Support team briefed on new features

## Communication Cadence by Role Interaction

| Interaction | Frequency | Owner | Format |
|---|---|---|---|
| Dev + QA sync | 2–3x per week | Project Manager | Standup or Slack |
| PM + Business Analyst | Weekly | Product Manager | Sync meeting |
| Release Manager + Dev/QA | Pre-release | Release Manager | Pre-flight checklist |
| Technical Writer + All | Per-feature | Technical Writer | Documentation review |
| Retrospective | End of sprint/release | Project Manager | Facilitated meeting |

## Escalation Paths by Role Conflict

### Scope vs. Timeline
**Involved:** Product Manager, Project Manager, Developers
- Escalate to: Product Lead + Project Sponsor
- Goal: Adjust scope, timeline, or resources

### Design vs. Technical Feasibility
**Involved:** UX/UI Designer, Developers
- Escalate to: Product Manager
- Goal: Find compromise that balances usability and effort

### Quality Concerns
**Involved:** QA/Tester, Developers, Release Manager
- Escalate to: Project Manager + Product Manager
- Goal: Decide on release timing or additional testing

### Documentation Gaps
**Involved:** Technical Writer, Developers, Product Manager
- Escalate to: Project Manager
- Goal: Allocate time for documentation before release

## When Roles Overlap: Decision Matrix

Use this matrix when responsibility is unclear:

| Decision | Primary Owner | Consulted | Informed |
|---|---|---|---|
| What to build | Product Manager | Stakeholders, Developers | All team |
| How to build it | Developers | Architects, QA | Product Manager |
| Is it done? | QA/Tester | Developers, Product Manager | All team |
| Can we ship it? | Release Manager | QA, Developers | Stakeholders |
| Is it usable? | UX/UI Designer | Developers, QA | Product Manager |
| Are requirements clear? | Business Analyst | Product Manager, Developers | All team |
| Are we on track? | Project Manager | All team | Stakeholders |

## Best Practices for Cross-Functional Collaboration

1. **Clarify ownership early:** At project kickoff, explicitly assign a primary owner for each phase and decision.
2. **Document decisions:** Use a decision log to record who decided what and why.
3. **Create feedback loops:** Design ceremonies (refinement, reviews, demos) that include all relevant roles.
4. **Respect expertise:** Defer to role experts on decisions within their domain (e.g., UX/UI Designer on usability).
5. **Communicate early:** Don't wait for formal meetings to flag concerns or dependencies.
6. **Use consistent templates:** Shared templates (user stories, acceptance criteria, test plans) reduce ambiguity.
7. **Measure handoff quality:** Track rework or escalations to identify weak handoff points.

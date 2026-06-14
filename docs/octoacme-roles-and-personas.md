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

## Release Manager

### Role Summary
Release Managers oversee deployment activities, ensure pre-release readiness, and coordinate timing across development, QA, and product teams. They own the go/no-go decision and drive communication throughout the release cycle.

### Responsibilities
- Schedule and coordinate deployment windows
- Own and execute release checklists and pre-flight validations
- Direct the go/no-go decision based on readiness criteria
- Communicate release status to all stakeholders
- Coordinate rollback procedures if issues arise post-deployment
- Track and document release metrics and lessons learned

### Goals
- Reduce deployment risk and unplanned downtime
- Ensure smooth, predictable releases
- Maintain clear visibility into release readiness and status

### Typical Communication
- Pre-release readiness reviews with Dev and QA
- Stakeholder release announcements and status updates
- Post-release retrospectives and metrics reporting
- Incident communication if rollback is needed

### Interactions
- Works closely with **Developers** to validate build readiness and coordinate timing
- Collaborates with **QA/Testers** to confirm acceptance criteria and smoke test completion
- Aligns with **Product Managers** on release scope and messaging
- Coordinates with **Project Managers** on milestone handoff and timeline adjustments

---

## Business Analyst

### Role Summary
Business Analysts bridge stakeholders and delivery teams by clarifying requirements, documenting user needs, and translating business objectives into actionable user stories and acceptance criteria.

### Responsibilities
- Gather and document requirements from stakeholders
- Translate business objectives into measurable success criteria
- Create detailed user stories with clear acceptance criteria
- Validate scope and identify gaps before development begins
- Participate in refinement sessions to clarify questions
- Ensure requirements align with project goals and constraints

### Goals
- Minimize rework and scope creep through clear requirements
- Accelerate development by reducing ambiguity
- Ensure solutions address the actual user need

### Typical Communication
- Stakeholder interviews and discovery sessions
- Requirements documentation and user story creation
- Backlog refinement and clarification discussions
- Acceptance criteria reviews with QA and Developers

### Interactions
- Interfaces between **Product Managers** (who set priorities) and **Developers** (who implement)
- Collaborates with **UX/UI Designers** to understand user context and usability needs
- Works with **QA/Testers** to ensure acceptance criteria are testable
- Engages **Stakeholders** to validate requirements and feedback

---

## UX/UI Designer

### Role Summary
UX/UI Designers ensure that features are usable, accessible, and visually consistent. They conduct user research, create designs and prototypes, and iterate based on feedback from users, stakeholders, and the delivery team.

### Responsibilities
- Conduct user research and usability studies
- Create wireframes, mockups, and prototypes
- Define design systems and ensure consistency across features
- Run design reviews with stakeholders and team
- Iterate designs based on feedback and usability testing
- Document design specifications for developer handoff
- Advocate for user needs and accessibility standards

### Goals
- Deliver intuitive, accessible user experiences
- Reduce support burden through clear, usable interfaces
- Establish a consistent, recognizable design language

### Typical Communication
- Design specification documents and wireframe reviews
- Usability research findings and recommendations
- Design feedback and iteration cycles
- Accessibility and design pattern guidance

### Interactions
- Collaborates with **Product Managers** on feature scope and user priorities
- Partners with **Business Analysts** to understand user context and acceptance criteria
- Works closely with **Developers** on design feasibility and implementation details
- Engages **QA/Testers** to validate usability and accessibility compliance

---

## QA/Tester

### Role Summary
QA/Testers validate that features meet acceptance criteria, identify defects, and ensure quality standards before release. They work independently from developers to provide objective quality assessment.

### Responsibilities
- Create and maintain test plans and test cases
- Execute manual and automated tests across feature sets
- Log, triage, and track defects through resolution
- Verify fixes and confirm readiness for release
- Test critical user flows and edge cases
- Validate acceptance criteria and Definition of Done
- Identify and document known issues and workarounds

### Goals
- Catch defects early and reduce production issues
- Ensure features meet stated acceptance criteria
- Provide confidence in release quality

### Typical Communication
- Test plans and test case documentation
- Defect reports with clear reproduction steps
- QA sign-off on feature readiness
- Test metrics and quality dashboards

### Interactions
- Partners with **Developers** to understand feature implementation and test edge cases
- Validates acceptance criteria defined by **Business Analysts** and **Product Managers**
- Collaborates with **UX/UI Designers** to test usability and accessibility
- Works with **Release Managers** to confirm smoke tests before deployment
- Engages **Project Managers** on timeline impacts of defect fixes

---

## Technical Writer

### Role Summary
Technical Writers own documentation standards and help produce clear, accurate user-facing and internal documentation. They work across teams to ensure technical changes are communicated and documented for both internal and external audiences.

### Responsibilities
- Draft and maintain user guides, API documentation, and help articles
- Review technical changes for clarity and completeness
- Create and enforce documentation standards and templates
- Translate complex technical concepts for non-technical audiences
- Maintain internal process documentation and knowledge bases
- Collaborate on release notes and change announcements
- Identify and close documentation gaps

### Goals
- Reduce support burden through clear, complete documentation
- Improve user adoption and confidence in features
- Maintain a consistent, accessible knowledge base

### Typical Communication
- Documentation drafts and content reviews
- Documentation standards and style guides
- Release notes and feature announcements
- Knowledge base and help center updates

### Interactions
- Collaborates with **Developers** to understand technical implementation and translate for users
- Works with **Product Managers** to understand feature goals and messaging
- Partners with **UX/UI Designers** to ensure documentation matches user interface
- Engages **Business Analysts** to capture and clarify business context
- Supports **Release Managers** with release notes and announcement content

---

## Role Interaction Map

```
┌──────────────────────────────────────────────────────────────────────┐
│                     STAKEHOLDERS & SPONSORS                          │
└──────────────────────────────────┬──────────────────────────────────┘
                   ┌────────────────┴─────────────────────────┐
         ┌────────┴──────────┐      ┌──────────┬─────────────┐
         │                   │      │          │             │
    ┌────▼──────────┐      ┌───────▼──┐   ┌──▼──────────┐  │
    │  Product     │      │  Project │   │ Stakeholder│  │
    │ Managers     │      │ Managers │   │ Management │  │
    └────┬──────────┘      └──────┬──┘   └──┬─────────┘  │
         │                        │         │           │
    ┌────┴──────────────────────┬─────────┴────────────┘
    │                           │
┌───▼────────────┐    ┌────────┴──────────────────────────┐
│   Business     │    │                                   │
│   Analysts     │    │  ┌──────────────────────────────┐ │
└────┬───────────┘    │  │   UX/UI Designers           │ │
     │                │  └──────────────────────────────┘ │
     └────────────────┼────────┬──────────────────────────┘
                      │        │
              ┌───────▼────────▼──────────────────┐
              │                                  │
          ┌───▼──────────────┐   ┌───────▼───────▼──────────┐
          │  Developers      │   │  QA/Testers            │
          └────────┬─────────┘   └───────────┬──────────────┘
                   │                         │
                   └──────────┬──────────────┘
                              │
                          ┌───▼────────────┐   ┌──────────────────┐
                          │ Release        │   │  Technical       │
                          │ Manager        │   │  Writers         │
                          └────────────────┘   └──────────────────┘
```

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Role Interaction Map to understand cross-functional dependencies and communication patterns.
- When designing workflows or defining responsibilities, ensure coverage across all relevant personas to minimize gaps and ambiguity.

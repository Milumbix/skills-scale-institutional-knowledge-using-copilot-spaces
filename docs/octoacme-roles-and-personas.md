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

## Additional Personas

The following personas support specialized functions in project delivery, ensuring comprehensive risk management, quality assurance, stakeholder engagement, and change adoption.

### Risk Manager

#### Role Summary
Risk Managers proactively identify, assess, track, and communicate project risks. They ensure mitigation strategies are in place and escalate critical risks to appropriate stakeholders.

#### Responsibilities
- Identify and document risks during project initiation and throughout execution
- Assess risk likelihood and impact using standardized criteria
- Develop and track mitigation plans with clear owners
- Maintain the risk register and ensure it's up-to-date
- Facilitate risk reviews during weekly syncs and milestone meetings
- Escalate high-impact risks to Project Managers and stakeholders

#### Primary Interactions
- **Coordinates with**: Project Managers (risk prioritization, status), Product Managers (scope/timeline risks), Developers (technical risks), Stakeholders (communication)
- **Escalation points**: Project Manager → Product Lead → Executive Sponsor
- **Reports to**: Project Manager

#### Acceptance Criteria / KPIs
- All identified risks are documented in the risk register within 24 hours
- High-priority risks have mitigation plans and owners assigned
- Risk register reviewed and updated weekly
- Zero critical risks without documented mitigation strategy
- Escalation SLA: Critical risks escalated within 4 hours

#### Example Engagement
**When to engage**: At project kickoff to set up risk identification process; when a technical dependency slips; when scope changes introduce new risks; during monthly risk review meetings.

---

### Stakeholder Engagement Lead

#### Role Summary
Stakeholder Engagement Leads ensure effective communication and alignment between the project team and all stakeholders. They manage expectations, gather feedback, and facilitate decision-making across organizational boundaries.

#### Responsibilities
- Identify and map all project stakeholders (influence, interest, communication needs)
- Develop and maintain the stakeholder engagement plan
- Schedule and facilitate stakeholder reviews and updates
- Gather and synthesize stakeholder feedback for the team
- Manage escalations and approvals requiring stakeholder sign-off
- Track stakeholder satisfaction and engagement metrics

#### Primary Interactions
- **Coordinates with**: Project Managers (status, timelines), Product Managers (roadmap, priorities), Executive Sponsors (strategic alignment), Cross-functional teams (dependencies)
- **Escalation points**: Project Manager → Executive Sponsor
- **Reports to**: Project Manager or Product Manager

#### Acceptance Criteria / KPIs
- Stakeholder engagement plan created and approved within first week
- 95%+ attendance rate at scheduled stakeholder reviews
- Feedback from stakeholders incorporated within 2 business days
- All stakeholders receive timely updates per agreed communication plan
- Stakeholder satisfaction score ≥ 4/5 at project milestones

#### Example Engagement
**When to engage**: During project initiation to identify stakeholders; before major milestone decisions; when scope changes require approval; when cross-team dependencies impact other groups; for quarterly business reviews.

---

### Quality Assurance Lead

#### Role Summary
Quality Assurance Leads ensure deliverables meet defined quality standards and acceptance criteria. They oversee testing strategies, defect management, and sign-off processes before releases.

#### Responsibilities
- Define quality standards and acceptance criteria with Product Managers
- Create and maintain test plans and testing coverage checklists
- Coordinate testing activities (functional, integration, regression, UAT)
- Manage defect triage, prioritization, and resolution tracking
- Conduct pre-release quality reviews and provide go/no-go recommendations
- Track quality metrics and advocate for quality improvements

#### Primary Interactions
- **Coordinates with**: Developers (defect reports, test environments), Product Managers (acceptance criteria), Project Managers (testing timelines), Release Managers (deployment readiness)
- **Escalation points**: Project Manager → Product Lead
- **Reports to**: Project Manager or Engineering Lead

#### Acceptance Criteria / KPIs
- Test plans created and reviewed before development begins
- 90%+ test coverage on critical user flows
- All P0/P1 defects resolved before release
- Zero production incidents due to insufficient testing in past 3 releases
- Release sign-off completed 24 hours before deployment

#### Example Engagement
**When to engage**: During planning to define acceptance criteria; before sprint/iteration starts to create test plans; during development for continuous testing; before release for final quality review and sign-off; after production incidents for root cause analysis.

---

### Change Champion

#### Role Summary
Change Champions drive adoption of new processes, tools, or features. They assess readiness, plan communications and training, and track adoption metrics to ensure successful change implementation.

#### Responsibilities
- Assess organizational readiness for change initiatives
- Develop comprehensive change adoption plans (communications, training, support)
- Create and deliver training materials and enablement sessions
- Monitor adoption metrics and gather user feedback
- Identify and address resistance or barriers to adoption
- Define and track go/no-go criteria for change rollouts

#### Primary Interactions
- **Coordinates with**: Product Managers (feature rollout), Training Teams (materials development), Support Teams (readiness), Project Managers (timelines), End Users (feedback)
- **Escalation points**: Project Manager → Product Lead → Change Management Office
- **Reports to**: Project Manager or Program Manager

#### Acceptance Criteria / KPIs
- Change readiness assessment completed 4 weeks before launch
- Training plan and materials delivered 2 weeks before rollout
- 80%+ of target users complete training before go-live
- Adoption rate reaches 70%+ within 30 days of launch
- User satisfaction with change process ≥ 4/5
- Rollback plan documented and communicated

#### Example Engagement
**When to engage**: When introducing new tools or processes; before major feature releases affecting many users; when process changes require behavioral shifts; during organizational transformations; for post-launch adoption tracking and optimization.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.


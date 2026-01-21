# Risk Management Checklist

This checklist provides a practical framework for identifying, assessing, tracking, and communicating project risks throughout the project lifecycle.

---

## Initial Risk Identification

Use this checklist during project initiation and planning phases:

- [ ] Review project scope and identify potential scope creep or ambiguity risks
- [ ] Assess technical complexity and identify technical debt or architecture risks
- [ ] Evaluate team capacity and identify resource availability risks
- [ ] Review dependencies on external teams, vendors, or services
- [ ] Identify regulatory, compliance, or security requirements that could impact timeline
- [ ] Assess stakeholder alignment and identify potential approval delays
- [ ] Review historical data from similar projects for common risk patterns
- [ ] Conduct risk brainstorming session with cross-functional team
- [ ] Document all identified risks in the risk register

---

## Risk Assessment Template

For each identified risk, complete the following assessment:

**Risk ID**: [AUTO-INCREMENT or use format: RISK-YYYY-###]

**Description**: [Clear, concise description of the risk event]

**Category**: [Technical / Resource / Schedule / Scope / External / Compliance]

**Likelihood**:
- **High**: >60% probability of occurring
- **Medium**: 30-60% probability of occurring  
- **Low**: <30% probability of occurring

**Impact**:
- **High**: Threatens project success, major scope/schedule/budget impact, >4 weeks delay
- **Medium**: Significant impact but recoverable, 1-4 weeks delay
- **Low**: Minimal impact, <1 week delay or minor workaround available

**Risk Score**: [Likelihood × Impact = Priority]
- High × High = **Critical** (address immediately)
- High × Med or Med × High = **High** (prioritize)
- Med × Med, High × Low, or Low × High = **Medium** (monitor closely)
- Low × Med or Med × Low = **Low** (track)
- Low × Low = **Minimal** (acknowledge)

**Owner**: [Name of person responsible for monitoring and mitigation]

**Mitigation Plan**: [Actions to reduce likelihood or impact]

**Contingency Plan**: [Backup plan if risk materializes]

**Status**: [Open / In Progress / Mitigated / Closed / Materialized]

---

## Example Risk Entries

### Example 1: Technical Dependency

- **Risk ID**: RISK-2026-001
- **Description**: Third-party API provider has history of outages during high-traffic periods, which could impact our integration testing and launch timeline
- **Category**: External
- **Likelihood**: Medium (40%)
- **Impact**: High (could delay launch by 2-3 weeks)
- **Risk Score**: High priority
- **Owner**: Technical Lead - Alex Chen
- **Mitigation Plan**: 
  - Implement circuit breaker pattern and retry logic
  - Create mock API endpoints for testing
  - Schedule testing during off-peak hours
  - Establish direct communication channel with vendor's reliability team
- **Contingency Plan**: Use cached responses and graceful degradation; delay launch by 1 sprint if needed
- **Status**: In Progress (mitigation actions underway)

### Example 2: Resource Constraint

- **Risk ID**: RISK-2026-002
- **Description**: Key frontend developer is scheduled for parental leave during final sprint, reducing team capacity by 30%
- **Category**: Resource
- **Likelihood**: High (90% - confirmed leave dates)
- **Impact**: Medium (could slow velocity but not block launch)
- **Risk Score**: High priority
- **Owner**: Project Manager - Jordan Lee
- **Mitigation Plan**:
  - Cross-train two other developers on frontend components (2 weeks before leave)
  - Prioritize frontend work in earlier sprints
  - Document all setup and deployment procedures
  - Arrange for part-time consulting support if needed
- **Contingency Plan**: Reduce scope of polish features; extend timeline by 1 week if critical
- **Status**: Open (mitigation scheduled)

---

## Mitigation Planning

For each risk requiring mitigation, document:

- [ ] Specific, actionable mitigation steps with deadlines
- [ ] Person responsible for each mitigation action
- [ ] Resources or budget needed for mitigation
- [ ] Success criteria (how you'll know mitigation worked)
- [ ] Trigger conditions that indicate risk is materializing
- [ ] Timeline to implement mitigation before risk could occur

**Mitigation Review Questions**:
- Will this mitigation reduce likelihood, impact, or both?
- Is the mitigation cost-effective relative to the risk impact?
- Does the mitigation introduce new risks?
- Can the mitigation be implemented in time?

---

## Monitoring & Reporting Cadence

### Daily/Ongoing
- [ ] Risk owners monitor trigger conditions for their assigned risks
- [ ] New risks identified during standup are immediately logged
- [ ] Critical risks are escalated immediately (within 4 hours)

### Weekly
- [ ] Review risk register at project sync meeting
- [ ] Update risk status, likelihood, and impact assessments
- [ ] Review progress on mitigation actions
- [ ] Add newly identified risks from the past week
- [ ] Archive or close mitigated risks
- [ ] Include top 3 risks in weekly status report

### Monthly/Milestone
- [ ] Conduct comprehensive risk review with stakeholders
- [ ] Validate that all risks still have appropriate owners
- [ ] Review risk trends (increasing/decreasing)
- [ ] Assess effectiveness of mitigation strategies
- [ ] Update risk management approach if needed

---

## Escalation Path

Follow this escalation path based on risk severity and status:

**Low & Medium Risks**:
1. Risk Owner monitors and implements mitigation
2. Report status to Project Manager weekly
3. Escalate to Project Manager if risk status worsens

**High Risks**:
1. Risk Owner implements mitigation with PM oversight
2. Project Manager briefs stakeholders weekly
3. Escalate to Product Lead if mitigation is blocked or ineffective

**Critical Risks**:
1. Immediate escalation to Project Manager (within 4 hours)
2. Project Manager escalates to Product Lead and Executive Sponsor (within 24 hours)
3. Emergency response team convened if risk materializes
4. Executive Sponsor approves contingency plan execution

**Escalation Triggers**:
- Risk score increases from Medium to High or High to Critical
- Mitigation actions are blocked or failing
- Risk materializes or is about to materialize
- Multiple related risks create compound threat
- Risk requires budget increase or scope change

---

## Risk Register Maintenance

Keep your risk register current and actionable:

- [ ] Use a shared, version-controlled document or project management tool
- [ ] Update status within 24 hours of any material change
- [ ] Archive closed risks (don't delete - useful for retrospectives)
- [ ] Link risks to related backlog items, milestones, or dependencies
- [ ] Tag risks with relevant labels (category, priority, status)
- [ ] Include "last updated" timestamp on each risk entry
- [ ] Review and prune risks that are no longer relevant

**Risk Register Location**: [Link to your project's risk register, e.g., GitHub Issues with label "risk", project board, or shared document]

---

## Related Documentation

- [OctoAcme Roles and Personas](./octoacme-roles-and-personas.md) - See Risk Manager persona
- [Risks and Communication](./octoacme-risks-and-communication.md) - Overview of risk management approach
- [Project Planning](./octoacme-project-planning.md) - Risk identification during planning phase
- [Execution and Tracking](./octoacme-execution-and-tracking.md) - Ongoing risk monitoring

---

**Last Updated**: 2026-01  
**Owner**: Project Management Team  
**Feedback**: Submit issues or PRs to improve this checklist

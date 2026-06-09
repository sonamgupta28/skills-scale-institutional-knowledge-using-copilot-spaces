# OctoAcme — Role Handoff Checklist

## Purpose
Provide checklists for common handoffs between roles to ensure clarity, completeness, and continuity.

## Product Manager → Development Team Handoff

**When**: At the start of a sprint or when a feature moves from planning to development.

### Before Handoff
- [ ] Problem statement is clear and documented
- [ ] Success metrics are defined and measurable
- [ ] Acceptance criteria are specific and testable
- [ ] Design (or design direction) is approved
- [ ] Dependencies are identified and communicated
- [ ] Timeline and priority are clear
- [ ] Relevant user research or feedback is shared

### During Handoff
- [ ] Product Manager answers questions from Developers
- [ ] Developers confirm they understand acceptance criteria
- [ ] Scrum Master documents any dependencies or risks
- [ ] Timeline is agreed upon

### After Handoff
- [ ] Developers have access to all required documentation
- [ ] Story is added to sprint backlog with acceptance criteria
- [ ] Product Manager is available for clarifications during development

---

## UX Designer → Development Team Handoff

**When**: Design is complete and development is ready to implement.

### Before Handoff
- [ ] Wireframes or mockups are finalized
- [ ] Design specs include colors, fonts, spacing, and interactions
- [ ] Accessibility requirements are documented (WCAG guidelines, screen reader support, etc.)
- [ ] Mobile/responsive behavior is defined
- [ ] Edge cases and error states are designed
- [ ] Design has been reviewed with Product Manager and key stakeholders

### During Handoff
- [ ] UX Designer presents design to development team
- [ ] Developers ask questions about implementation complexity
- [ ] UX Designer clarifies intent and rationale
- [ ] Developers confirm they understand the spec

### After Handoff
- [ ] Design files are accessible to Developers (Figma, Adobe XD, etc.)
- [ ] UX Designer is available for design clarifications
- [ ] Developers know who to contact for design decisions during implementation

---

## Development Team → QA/Testing Handoff

**When**: Feature is code-complete and ready for testing.

### Before Handoff
- [ ] Code has been reviewed and approved in PR
- [ ] Unit tests pass and coverage is adequate
- [ ] Code is deployed to a testing environment
- [ ] Acceptance criteria are clear in the PR or issue
- [ ] Any known limitations or edge cases are documented
- [ ] Build/deployment logs are available if needed

### During Handoff
- [ ] Developer walks QA through the feature and acceptance criteria
- [ ] Developer demonstrates the happy path
- [ ] QA asks questions about edge cases and error handling
- [ ] Test environment access is confirmed

### After Handoff
- [ ] QA has a copy of acceptance criteria and design specs
- [ ] QA knows who to contact for technical questions
- [ ] QA has access to relevant logs and debugging tools

---

## QA/Testing → Development Team (Bug Report) Handoff

**When**: QA finds a bug that needs developer attention.

### Before Handoff
- [ ] Bug is reproducible with clear steps
- [ ] Expected vs. actual behavior is documented
- [ ] Screenshots or videos of the issue are attached
- [ ] Affected browsers/devices are noted
- [ ] Severity is assessed (critical, high, medium, low)
- [ ] Bug is logged in issue tracking system

### During Handoff
- [ ] QA and Developer discuss the bug together
- [ ] Developer reproduces the issue
- [ ] Root cause is identified
- [ ] Timeline for fix is agreed upon

### After Handoff
- [ ] Bug is logged with acceptance criteria for the fix
- [ ] Developer will ping QA when fix is ready for re-testing

---

## Security Lead → Development Team Handoff

**When**: Security review is complete or security requirements need to be implemented.

### Before Handoff
- [ ] Security threat model is documented
- [ ] Security requirements are specific and testable
- [ ] Code or design review findings are categorized (critical, high, medium, low)
- [ ] Remediation steps are clear
- [ ] Timeline for fixes is realistic

### During Handoff
- [ ] Security Lead explains threat model and requirements
- [ ] Developers ask questions about feasibility and trade-offs
- [ ] Security Lead clarifies intent and rationale
- [ ] Developers confirm understanding

### After Handoff
- [ ] Findings are logged as issues or acceptance criteria
- [ ] Security Lead is available for questions during implementation
- [ ] Developers know the escalation path for security questions

---

## DevOps Engineer → Development Team (Release) Handoff

**When**: Feature is ready for release and deployment is being coordinated.

### Before Handoff
- [ ] Deployment checklist is complete
- [ ] CI/CD pipeline is green
- [ ] Staging environment mirrors production
- [ ] Smoke tests are defined and documented
- [ ] Rollback plan is documented
- [ ] Monitoring and alerting are configured
- [ ] Deployment window is scheduled (if needed)

### During Handoff
- [ ] DevOps Engineer reviews deployment plan with team
- [ ] Developers confirm they have tested on staging
- [ ] DevOps Engineer explains rollback procedure
- [ ] Deployment timing and notification plan are confirmed

### After Handoff
- [ ] Developers are notified when deployment is complete
- [ ] Post-deployment validation is performed
- [ ] Any issues are escalated immediately

---

## Data Analyst → Team (Metrics) Handoff

**When**: A feature ships and outcome measurement needs to begin.

### Before Handoff
- [ ] Success metrics are defined and documented
- [ ] Instrumentation code is merged and deployed
- [ ] Dashboards are configured
- [ ] Alerts are set for anomalies
- [ ] Baseline metrics are captured (before release)

### During Handoff
- [ ] Data Analyst walks team through dashboard
- [ ] Team understands what metrics mean and how to interpret them
- [ ] Questions about data collection are answered

### After Handoff
- [ ] Data Analyst monitors dashboards during rollout
- [ ] Data Analyst alerts team to unexpected changes
- [ ] Team has access to dashboards and reports

---

## Customer Support → Product Team (Feedback) Handoff

**When**: Customer feedback needs to inform prioritization or troubleshooting.

### Before Handoff
- [ ] Customer feedback is summarized and categorized (bug, feature request, usability issue)
- [ ] Frequency/impact is quantified (how many users affected, how critical)
- [ ] Example quotes or screenshots from customers are included
- [ ] Suggested workarounds are documented (if applicable)

### During Handoff
- [ ] Customer Support explains context and customer impact
- [ ] Product Manager and Developers discuss prioritization
- [ ] Severity and timeline for response are agreed upon

### After Handoff
- [ ] Feedback is logged as an issue if it requires development work
- [ ] Customer Support is notified of timeline for response
- [ ] Customer Support communicates back to customers

---

## Template for Any Handoff

Use this template for any handoff not covered above:

```
**From Role:** [e.g., UX Designer]
**To Role:** [e.g., Developers]
**When:** [e.g., After design is approved]

**What is being handed off:**
- [ ] Item 1
- [ ] Item 2
- [ ] Item 3

**Key context & decisions:**
- [Key decision 1 and why it was made]
- [Key assumption or constraint]

**Next steps:**
- [What the receiving role should do]
- [Timeline for completion]
- [Who to contact for questions]

**Success criteria:**
- [How we know the handoff was successful]
```

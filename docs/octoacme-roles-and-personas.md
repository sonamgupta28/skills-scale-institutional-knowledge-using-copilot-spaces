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

## UX Designer

### Role Summary
UX Designers translate user needs, business requirements, and technical constraints into intuitive product designs and user flows. They advocate for user experience throughout the product lifecycle.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and design specifications
- Collaborate with Product Managers and Developers on design feasibility
- Document user insights and design rationale
- Participate in design reviews and iteration cycles
- Ensure accessibility and usability standards are met

### Goals
- Maximize user satisfaction and product adoption
- Reduce user friction and support costs
- Balance user needs with business objectives and technical constraints

### Typical Communication
- Design critiques and feedback sessions
- User research findings and recommendations
- Collaboration with PM, Developers, and QA on implementation details

### Key Interactions
- **Product Manager**: Align on user needs, business goals, and prioritization
- **Developers**: Discuss design feasibility, technical constraints, and implementation
- **QA/Testing**: Define acceptance criteria for design quality
- **Customer Support**: Incorporate user feedback and common pain points

---

## Scrum Master

### Role Summary
Scrum Masters facilitate agile ceremonies, remove process impediments, and enable continuous team improvement. They coach teams on agile practices and foster a culture of collaboration and transparency.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove blockers and process impediments
- Coach team members on agile practices and self-organization
- Track team velocity and burndown metrics
- Escalate risks and dependencies to Project Manager
- Foster psychological safety and encourage feedback

### Goals
- Maximize team efficiency and predictability
- Enable sustainable pace and continuous improvement
- Reduce dependencies and hand-offs between teams

### Typical Communication
- Agile ceremonies and team coaching
- Impediment logs and escalation reports
- Retrospective action items and follow-ups

### Key Interactions
- **Developers**: Coach on practices, facilitate collaboration
- **Project Manager**: Escalate blockers, report on team health
- **Other Scrum Masters**: Coordinate cross-team dependencies

---

## DevOps Engineer

### Role Summary
DevOps Engineers maintain and improve build, deployment, and monitoring infrastructure. They drive automation, reliability, and observability to enable rapid, safe releases.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code and deployments
- Monitor application health and performance
- Implement and test rollback/disaster recovery plans
- Collaborate with Developers on deployment readiness
- Troubleshoot production issues and post-incident reviews

### Goals
- Enable frequent, reliable deployments
- Minimize deployment risk and mean time to recovery
- Improve observability and incident response

### Typical Communication
- Deployment planning and coordination
- Infrastructure and pipeline documentation
- Incident response and post-mortems

### Key Interactions
- **Developers**: Support deployment readiness and troubleshooting
- **QA/Testing**: Coordinate smoke tests and release validation
- **Project Manager**: Plan deployment windows and communicate status
- **Security Lead**: Implement security scanning and hardening

---

## Security Lead

### Role Summary
Security Leads ensure that security practices and requirements are integrated throughout product development. They identify risks, recommend controls, and support incident response.

### Responsibilities
- Perform threat modeling and security reviews
- Review code and architecture for vulnerabilities
- Collaborate on security requirements and acceptance criteria
- Drive security incident response and investigation
- Maintain security runbooks and incident playbooks
- Stay current on emerging threats and best practices

### Goals
- Reduce security risk and data breach likelihood
- Enable fast, confidently-executed releases
- Foster a security-conscious team culture

### Typical Communication
- Security reviews and threat modeling sessions
- Vulnerability reports and remediation plans
- Security incident communication and post-mortems

### Key Interactions
- **Developers**: Security code reviews and guidance
- **Product Manager**: Prioritize security requirements
- **DevOps Engineer**: Implement security controls and scanning
- **Project Manager**: Escalate security risks and timelines

---

## Customer Support

### Role Summary
Customer Support represents the voice of the user post-launch, handling feedback, questions, and issues. They bridge the gap between customers and the product team, informing improvements and priorities.

### Responsibilities
- Monitor support channels and triage user issues
- Identify bugs, feature requests, and user pain points
- Communicate trends and patterns to Product Manager and Developers
- Reproduce and document issues for the development team
- Provide customer context during prioritization discussions
- Escalate urgent user-impacting issues

### Goals
- Maximize customer satisfaction and retention
- Reduce support costs through improved product quality
- Accelerate product improvements informed by user feedback

### Typical Communication
- Support channel monitoring and escalations
- Trend reports and user feedback summaries
- Collaboration on urgent issues and workarounds

### Key Interactions
- **Product Manager**: Provide user feedback and usage patterns
- **Developers**: Debug issues and communicate fixes
- **Project Manager**: Escalate critical customer-impacting issues
- **UX Designer**: Report usability challenges and feature requests

---

## Data Analyst

### Role Summary
Data Analysts measure project outcomes and product impact through metrics and insights. They support data-driven decision-making and help teams understand success through evidence.

### Responsibilities
- Define success metrics and KPIs aligned with business goals
- Build dashboards and reports for project and product visibility
- Analyze data to support hypothesis testing and prioritization
- Conduct post-release analysis and communicate results
- Support retrospectives with quantitative insights
- Surface trends and anomalies that inform next steps

### Goals
- Enable data-driven prioritization and decisions
- Measure project and product impact with evidence
- Accelerate learning through rapid feedback loops

### Typical Communication
- Metrics dashboards and reporting
- Data analysis findings and recommendations
- Collaboration on defining and measuring success

### Key Interactions
- **Product Manager**: Define success metrics and analyze outcomes
- **Project Manager**: Report on project health and progress
- **Developers**: Support performance analysis and optimization
- **DevOps Engineer**: Analyze system performance and reliability

---

## Cross-Functional Role Interactions

### Initiative Kickoff
When starting a new project or feature:
- **Product Manager** defines the problem, goals, and success metrics
- **Project Manager** creates timeline and coordinates team
- **UX Designer** conducts user research and proposes solutions
- **Developers** assess technical feasibility
- **Data Analyst** defines how success will be measured
- **Security Lead** identifies security requirements early

### Execution Phase
- **Developers** implement features in collaboration with **UX Designer**
- **Scrum Master** facilitates daily coordination and removes blockers
- **DevOps Engineer** prepares infrastructure and CI/CD pipelines
- **Data Analyst** tracks progress metrics
- **Customer Support** gathers early feedback from pilots or beta users

### Release & Rollout
- **DevOps Engineer** coordinates deployment with **Project Manager**
- **Security Lead** validates security posture
- **QA/Testing** runs smoke tests and acceptance criteria
- **Customer Support** prepares messaging and support for launch
- **Data Analyst** sets up monitoring dashboards

### Post-Release & Learning
- **Data Analyst** measures outcomes against success metrics
- **Customer Support** monitors for issues and user feedback
- **Developers** respond to bugs and urgent requests
- **Team** conducts retrospective to improve next cycle

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference the Cross-Functional Role Interactions section to understand how roles collaborate throughout a project lifecycle.

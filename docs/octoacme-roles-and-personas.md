# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Core Roles

### Developers

#### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

#### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

#### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

#### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

### Product Managers

#### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

#### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

#### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

#### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

### Project Managers

#### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

#### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

#### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

#### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Supporting Roles

### UX Designer

#### Role Summary
UX Designers shape user experiences by creating intuitive, accessible interfaces and workflows. They collaborate across product, engineering, and QA to ensure features are usable and aligned with user needs.

#### Responsibilities
- Conduct user research and usability testing
- Create wireframes, prototypes, and design specifications
- Ensure accessibility standards and usability best practices
- Participate in design reviews with cross-functional teams
- Gather and incorporate user feedback during iterations

#### Goals
- Deliver delightful, intuitive user experiences
- Reduce support friction and improve user adoption
- Maintain design consistency and accessibility compliance

#### Interactions
- **With Product Managers**: Collaborate on feature requirements, user stories, and success metrics
- **With Developers**: Provide design specifications, discuss implementation feasibility, review technical implementations
- **With QA/Testing**: Partner on usability test plans, validate user flows, gather feedback on acceptance criteria
- **With Support Lead**: Incorporate user pain points and feature requests from support interactions

#### Typical Communication
- Design reviews and critique sessions
- Figma/design system documentation
- User research findings and recommendations
- Feedback on prototype and implementation quality

---

### DevOps Engineer

#### Role Summary
DevOps Engineers automate deployment pipelines, ensure system reliability, and maintain consistent development, staging, and production environments. They bridge development and operations to enable rapid, reliable releases.

#### Responsibilities
- Design and maintain CI/CD pipelines
- Automate infrastructure provisioning and deployment
- Monitor system performance, uptime, and reliability
- Manage environment consistency across dev, staging, and production
- Respond to incidents and coordinate rollbacks when needed
- Document runbooks and deployment procedures

#### Goals
- Enable fast, safe deployments
- Reduce manual toil and human error
- Maintain high system availability and observability
- Support blameless incident response

#### Interactions
- **With Developers**: Review code for deployment readiness, provide CI/CD feedback, support debugging of pipeline failures
- **With Project Managers**: Report deployment status and risks, coordinate release windows, escalate infrastructure blockers
- **With QA/Testing**: Provision test environments, support performance testing, ensure staging parity with production
- **With Security**: Implement security scanning in pipelines, manage secrets and access controls

#### Typical Communication
- Deployment status and runbooks
- Infrastructure-as-code documentation (Terraform, Kubernetes, etc.)
- Incident post-mortems and action items
- Release notes with deployment instructions

---

### Data Analyst

#### Role Summary
Data Analysts measure product impact and generate actionable insights. They support data-driven decision-making by analyzing user behavior, system performance, and success metrics defined in project charters.

#### Responsibilities
- Define and track key performance indicators (KPIs) and success metrics
- Analyze user behavior and engagement data
- Create dashboards and reports for stakeholders
- Support A/B testing and experimentation
- Identify trends, anomalies, and opportunities for improvement
- Provide data-driven recommendations to product and business teams

#### Goals
- Empower teams with clear, actionable insights
- Enable evidence-based prioritization and iteration
- Measure and communicate product impact
- Support continuous improvement culture

#### Interactions
- **With Product Managers**: Provide metrics on feature adoption, user satisfaction, and business impact; support prioritization decisions
- **With Developers**: Define instrumentation requirements, support debugging performance issues, validate data collection accuracy
- **With Project Managers**: Report on project success metrics, track progress toward milestones, escalate concerning trends
- **With UX Designer**: Analyze usability metrics, support user research findings, validate design changes impact

#### Typical Communication
- Weekly/monthly dashboard updates
- Data analysis reports and recommendations
- Instrumentation requirements and specifications
- Ad-hoc analysis for decision support

---

### Support Lead

#### Role Summary
Support Leads are the voice of the customer. They triage support issues, identify patterns and recurring problems, and close the feedback loop between users and the product and engineering teams.

#### Responsibilities
- Manage and prioritize support tickets and escalations
- Identify recurring issues and trends
- Escalate bugs and feature requests to engineering and product
- Collaborate on bug reproductions and root cause analysis
- Communicate fixes and workarounds to users
- Gather and synthesize user feedback for product improvement

#### Goals
- Reduce user friction and support volume
- Ensure rapid response to critical issues
- Surface user needs and pain points to product team
- Maintain customer satisfaction and trust

#### Interactions
- **With Developers**: Collaborate on bug reproductions, provide detailed issue information, validate fixes before release
- **With Product Managers**: Highlight high-impact feature requests, communicate user pain points, prioritize backlog based on support trends
- **With Project Managers**: Report escalations and blockers, provide user impact assessment, coordinate urgent fixes
- **With UX Designer**: Provide user feedback on usability issues, highlight friction points, validate improvements address user needs

#### Typical Communication
- Support dashboards and ticket metrics
- Weekly support summary reports
- Escalations and bug reports with reproduction steps
- User feedback compilations and synthesis

---

## Role Interactions Matrix

| Role | Works closely with | Primary touchpoints |
|------|-------------------|-------------------|
| **Developer** | DevOps, QA, PdM, UX Designer | Code reviews, standup, design reviews, incident response |
| **Product Manager** | PdM, Project Manager, Stakeholders | Weekly sync, roadmap planning, requirements |
| **Project Manager** | PM, PdM, DevOps, Support Lead | Daily standup, risk register, status reporting |
| **UX Designer** | Product Manager, Developers, QA, Support Lead | Design reviews, prototype feedback, usability testing |
| **DevOps Engineer** | Developers, Project Manager, QA | CI/CD, incident response, deployment coordination |
| **Data Analyst** | Product Manager, Project Manager, Developers, UX Designer | Metrics reporting, experimentation, dashboard reviews |
| **Support Lead** | Developers, Product Manager, Project Manager, UX Designer | Bug triage, user feedback, escalation management |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Reference interactions matrix when planning cross-functional collaboration and communication paths.
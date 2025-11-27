# OctoAcme — Risk Management & Communication

## Purpose
Explain how to identify, manage, and communicate risks and dependencies.

## Risk Register
Maintain a simple table with:
- ID
- Description
- Impact (High/Med/Low)
- Likelihood (High/Med/Low)
- Owner
- Mitigation plan
- Status

## Risk Lifecycle
- Identify: during planning and ongoing execution
- Assess: estimate impact and likelihood
- Mitigate: reduced via actions, contingency plans
- Monitor: review at weekly syncs and update status

## Role-Specific Risk Management Responsibilities

### Project Manager
- Owns and maintains the Risk Register
- Facilitates risk identification sessions
- Monitors risk status and escalates high-priority risks
- Coordinates cross-team mitigation efforts

### Technical Lead
- Identifies technical risks (architecture, scalability, security)
- Assesses technical feasibility and complexity
- Proposes technical mitigation strategies
- Monitors technical debt and performance risks

### Product Manager
- Identifies market and business risks
- Assesses impact on product strategy and customer value
- Makes prioritization decisions based on risk/reward
- Communicates risks to stakeholders

### Business Analyst
- Identifies requirements and scope risks
- Assesses impact of requirements changes
- Flags misalignment between business needs and solution

### Scrum Master / Delivery Facilitator
- Identifies process and team velocity risks
- Raises capacity and dependency risks
- Facilitates risk discussions in retrospectives

### UX/UI Designer
- Identifies usability and accessibility risks
- Flags design feasibility concerns early
- Assesses risks to user experience

### Support / Customer Success
- Identifies customer satisfaction and adoption risks
- Reports emerging production issues and trends
- Assesses impact of releases on customer experience

## Stakeholder Communication
- Identify stakeholder groups and communication needs (e.g., engineering, sales, support)
- Provide regular updates (weekly or milestone-based)
- Use a single source of truth (project README or release doc) for status

## Role-Specific Communication Responsibilities

### Project Manager
- Primary owner of stakeholder communication
- Sends weekly status updates
- Coordinates cross-team communications
- Manages project documentation

### Product Manager
- Communicates product vision and roadmap updates
- Updates on feature prioritization changes
- Shares customer insights and metrics
- Leads stakeholder briefings on product strategy

### Technical Lead
- Communicates technical decisions via Architecture Decision Records (ADRs)
- Provides technical risk updates
- Shares technical standards and best practices documentation

### Scrum Master / Delivery Facilitator
- Reports team metrics and velocity trends
- Communicates process improvements
- Shares retrospective action items and outcomes

### Business Analyst
- Documents requirements and maintains requirements traceability
- Communicates requirements changes to team
- Provides stakeholder interview summaries

### UX/UI Designer
- Shares design updates and user research findings
- Presents prototypes and designs to stakeholders
- Documents design decisions and rationale

### Support / Customer Success
- Provides customer feedback summaries
- Communicates release impacts to customers
- Shares support metrics and trends

## Communication Templates
Weekly Status Template:
- Progress this week:
- Next steps:
- Risks & blockers:
- Ask / decisions needed:

Incident Communication
- Triage summary
- Actions being taken
- Expected timeline
- Post-incident blameless retrospective scheduled

## Escalation Paths
- Team-level -> PM -> Product Lead -> Sponsor
- For security incidents, follow the security incident runbook and notify Security on-call

### Escalation Paths by Risk Type

**Technical Escalation**
- Developer -> Technical Lead -> Architecture Team -> Engineering Manager -> CTO

**Requirements/Scope Escalation**
- Business Analyst -> Product Manager -> Product Lead -> Stakeholder/Sponsor

**Delivery/Timeline Escalation**
- Scrum Master -> Project Manager -> Product Lead -> Sponsor

**Design/UX Escalation**
- UX/UI Designer -> Product Manager / Technical Lead -> Design Lead -> Product Lead

**Customer Impact Escalation**
- Support/Customer Success -> Product Manager / Project Manager -> Product Lead -> Executive Sponsor

**Security Incident**
- Any team member -> Security On-call -> Incident Commander -> CISO (follow security runbook)

**Cross-Team Dependency**
- Project Manager coordinates with other PMs -> Product Leads (if unresolved) -> Sponsors

---

**Related**: Role-specific risk and communication responsibilities added based on [Issue #4: Adding more personas and roles to the project management processes](https://github.com/JaimeBudi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to clarify accountability and escalation paths.

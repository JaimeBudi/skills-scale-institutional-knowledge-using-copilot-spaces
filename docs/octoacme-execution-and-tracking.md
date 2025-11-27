# OctoAcme — Execution & Tracking

## Purpose
Guidance for managing day-to-day execution and tracking progress toward project milestones.

## Team Rhythm
- Daily standups (15 min) — focus on progress, blockers, dependencies
- Weekly delivery sync — show progress, updates, and flagged risks
- Demo/Review at the end of each sprint or milestone

### Role Participation in Team Ceremonies

**Daily Standups**
- **Developers**: Share progress, identify blockers, coordinate work
- **Technical Lead**: Provide technical guidance on blockers, review technical decisions
- **Scrum Master/Delivery Facilitator**: Facilitate standup, track action items, remove impediments
- **UX/UI Designer**: Update on design deliverables, coordinate with developers on implementation
- **Business Analyst**: Available to clarify requirements as needed
- **Project Manager**: Monitor progress, note risks and dependencies

**Weekly Delivery Sync**
- **Project Manager**: Lead sync, present status, review risk register
- **Product Manager**: Share product updates, prioritization changes
- **Technical Lead**: Report technical risks, architecture decisions
- **Scrum Master**: Present team metrics (velocity, burndown), process improvements
- **Support/Customer Success**: Share customer feedback and production issues
- **All team members**: Demo completed work, discuss upcoming priorities

## Workflows
- Use the project board (e.g., GitHub Projects) with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Pull Request workflow:
  - Small PRs (<= 400 lines when possible)
  - Include issue link and acceptance criteria in PR description
  - Run automated tests and linting in CI before requesting review
  - Require at least one approval before merging (or team-defined policy)

## Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Quality Ownership by Role
- **Developers**: Write unit and integration tests, fix bugs
- **Technical Lead**: Review code quality, enforce standards, approve architecture changes
- **QA/Testers**: Execute test plans, validate acceptance criteria
- **UX/UI Designer**: Validate design implementation, check accessibility
- **Business Analyst**: Verify business requirements are met, support UAT
- **Support/Customer Success**: Provide real-world usage scenarios for testing

## Reporting & Metrics
- Track velocity and burndown
- Monitor success metrics identified in the Project One-pager
- Use dashboards for key signals (errors, latency, usage)

## Blocker Escalation
- Level 1: Team-level triage in daily standup (Scrum Master facilitates resolution)
- Level 2: PM escalates to Product Lead and dependent teams (Technical Lead for technical blockers)
- Level 3: Sponsor-level escalation for business-impacting issues

### Blocker Types and Ownership
- **Technical blockers**: Technical Lead owns resolution, may escalate to architecture team
- **Requirements clarity**: Business Analyst works with Product Manager to clarify
- **Design blockers**: UX/UI Designer coordinates with stakeholders or users
- **Resource/capacity blockers**: Scrum Master and Project Manager coordinate with management
- **Dependency blockers**: Project Manager coordinates with external teams
- **Production issues**: Support/Customer Success triages, escalates to development team

## Execution Checklist
- [ ] Branching and PR conventions documented in repo
- [ ] CI configured for tests and lint
- [ ] Regular demos scheduled
- [ ] Risk register updated weekly
- [ ] All key roles participating in team ceremonies
- [ ] Clear ownership for different blocker types
- [ ] Design reviews scheduled with UX/UI Designer
- [ ] Requirements clarification process established with Business Analyst

---

**Related**: Role-specific workflows and coordination added based on [Issue #4: Adding more personas and roles to the project management processes](https://github.com/JaimeBudi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to clarify execution responsibilities.

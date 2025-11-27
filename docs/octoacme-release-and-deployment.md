# OctoAcme — Release & Deployment Guide

## Purpose
Standardize how OctoAcme releases features to production to reduce risk and improve observability.

## Release Types
- Patch: hotfixes addressing critical production issues
- Minor: incremental features and improvements
- Major: significant functionality or breaking changes

## Pre-release requirements
- All acceptance criteria met and PRs merged
- Passing CI and security scans
- Release notes drafted
- Rollback / mitigation plan documented
- Smoke tests prepared

## Role-Specific Pre-Release Responsibilities

### Project Manager
- Coordinates release timeline and stakeholder communication
- Ensures all release checklist items are completed
- Schedules deployment window and coordinates resources

### Technical Lead
- Reviews and approves final code changes
- Validates technical readiness and performance benchmarks
- Ensures rollback procedures are tested and documented

### Developers
- Complete final PRs and code reviews
- Fix any critical bugs identified in staging
- Participate in deployment execution if needed

### QA/Testers
- Execute final test plan in staging environment
- Validate all acceptance criteria are met
- Perform smoke tests and regression testing

### Business Analyst
- Validates that delivered features meet business requirements
- Confirms acceptance criteria completion
- Supports UAT sign-off if required

### UX/UI Designer
- Reviews final implementation for design fidelity
- Validates accessibility standards are met
- Approves visual and interaction quality

### Product Manager
- Provides final go/no-go decision
- Reviews and approves release notes
- Plans release communication to customers

### Scrum Master / Delivery Facilitator
- Ensures team readiness for deployment
- Facilitates pre-release review meeting
- Tracks deployment metrics

### Support / Customer Success
- Reviews release notes and customer communications
- Prepares support team for new features
- Plans customer onboarding or training if needed

## Deployment Checklist
- [ ] Deployment window scheduled (if needed)
- [ ] Backup or snapshot (if applicable)
- [ ] Deploy to staging and run smoke tests
- [ ] Deploy to production (automated pipeline preferred)
- [ ] Run post-deploy verifications
- [ ] Announce release to stakeholders and support
- [ ] Technical Lead approves deployment readiness
- [ ] Product Manager provides go/no-go approval
- [ ] Support/Customer Success team briefed on changes
- [ ] Monitoring and alerting validated

## Rollback & Incident Playbook
- If a deployment fails or causes a critical issue:
  - Trigger incident response and notify on-call
  - Rollback to last known-good release if necessary
  - Triage root cause and capture action items

### Incident Response Roles

**Incident Commander** (typically Project Manager or Technical Lead)
- Coordinates incident response
- Makes rollback decisions
- Communicates with stakeholders

**Technical Lead & Developers**
- Execute rollback if needed
- Investigate root cause
- Implement fixes

**Support / Customer Success**
- Monitors customer impact
- Communicates with affected customers
- Triages incoming support requests

**Product Manager**
- Assesses business impact
- Decides on communication strategy
- Prioritizes incident resolution vs. other work

**Scrum Master**
- Facilitates post-incident retrospective
- Tracks action items from incident
- Ensures blameless culture

---

**Related**: Role-specific release responsibilities added based on [Issue #4: Adding more personas and roles to the project management processes](https://github.com/JaimeBudi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to clarify deployment accountability.

## Release Notes Template
- Release name / number:
- Date:
- Summary:
- Notable changes:
- Migration steps (if any):
- Known issues:

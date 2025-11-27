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

---

## Technical Lead

### Role Summary
Technical Leads oversee technical design and architecture decisions, ensuring code quality, technical standards, and best practices are upheld across the team. They serve as the primary technical authority, supporting developers with complex problem-solving and coordinating technology evaluations.

### Responsibilities
- Design and review technical architecture and system designs
- Establish and enforce code quality standards and best practices
- Mentor developers on technical challenges and problem-solving
- Evaluate and recommend technologies, libraries, and tools
- Lead technical design reviews and architectural discussions
- Identify technical debt and propose refactoring strategies
- Ensure scalability, performance, and security considerations are addressed

### Goals
- Maintain high technical quality and architectural consistency
- Enable team productivity through technical guidance and tooling
- Balance technical excellence with delivery timelines
- Foster technical growth and knowledge sharing within the team

### Typical Communication
- Technical design documents and architecture decision records (ADRs)
- Code review feedback and technical standards documentation
- Technical risk assessments during planning sessions
- Architecture walkthroughs and technical onboarding sessions

### Interactions with Other Roles
- **Developers**: Provides technical guidance, code review, and mentorship; collaborates on implementation approaches and problem-solving
- **Project Managers**: Provides technical feasibility assessments, effort estimates for complex work, and identifies technical risks and dependencies
- **Product Managers**: Advises on technical constraints and opportunities; helps evaluate feature feasibility and technical trade-offs
- **Business Analyst**: Translates business requirements into technical requirements and helps identify technical considerations for requirements
- **UX/UI Designer**: Collaborates on technical feasibility of designs and provides guidance on performance and technical constraints

### Example Scenario
During sprint planning, a Technical Lead reviews proposed features and identifies that a new integration requires architectural changes. They create a technical design document outlining the approach, conduct a design review with the development team, and work with the Project Manager to adjust timelines accordingly. They mentor a junior developer through the implementation, ensuring quality standards are met through thorough code reviews.

---

## Business Analyst

### Role Summary
Business Analysts serve as the bridge between business stakeholders and the technical team. They gather, refine, and document business requirements, analyze processes, and ensure that solutions align with business objectives and user needs.

### Responsibilities
- Elicit and document business requirements from stakeholders
- Analyze business processes and identify improvement opportunities
- Create detailed functional specifications and acceptance criteria
- Validate requirements with stakeholders and ensure clarity
- Facilitate requirements workshops and discovery sessions
- Maintain traceability between business needs and delivered features
- Support user acceptance testing (UAT) coordination

### Goals
- Ensure clear, complete, and testable requirements
- Reduce ambiguity and rework through thorough analysis
- Maximize business value delivery through well-defined requirements
- Bridge communication gaps between business and technical teams

### Typical Communication
- Requirements documents and user stories with detailed acceptance criteria
- Process flow diagrams and business process documentation
- Stakeholder interview summaries and requirements workshops
- UAT plans and test scenarios

### Interactions with Other Roles
- **Product Managers**: Collaborates on product vision and feature prioritization; provides detailed requirements analysis for roadmap items
- **Developers**: Clarifies requirements, answers questions during implementation, and validates delivered functionality
- **Project Managers**: Helps define scope, identifies dependencies, and supports timeline estimation
- **Stakeholders**: Primary liaison for requirements gathering, validation, and change management
- **QA/Testers**: Defines acceptance criteria and supports test case development
- **UX/UI Designer**: Ensures designs meet business requirements and user needs

### Example Scenario
A Business Analyst facilitates a requirements workshop with stakeholders for a new reporting feature. They document detailed user stories with acceptance criteria, create process flow diagrams, and work with the UX Designer to validate mockups against business needs. During development, they clarify edge cases with developers and coordinate UAT sessions to validate the implementation meets stakeholder expectations.

---

## Scrum Master / Delivery Facilitator

### Role Summary
The Scrum Master (or Delivery Facilitator) serves as a servant-leader who facilitates agile ceremonies, removes delivery blockers, and coaches the team on agile best practices. They focus on team productivity, continuous improvement, and adherence to agreed-upon processes.

### Responsibilities
- Facilitate agile ceremonies (standups, planning, retrospectives, demos)
- Remove impediments and blockers that hinder team progress
- Coach team members on agile principles and practices
- Shield the team from external distractions and context-switching
- Track and visualize team metrics (velocity, burndown, cycle time)
- Foster a collaborative and self-organizing team culture
- Drive continuous improvement through retrospectives and action items

### Goals
- Maximize team velocity and predictability
- Create a productive, collaborative team environment
- Ensure process adherence while maintaining flexibility
- Enable the team to deliver high-quality work sustainably

### Typical Communication
- Daily standup facilitation and follow-up on blockers
- Sprint metrics and team health indicators
- Process improvement proposals and retrospective summaries
- Escalation of persistent blockers to leadership

### Interactions with Other Roles
- **Project Managers**: Partners on delivery coordination, shares team metrics, and escalates organizational blockers
- **Developers**: Facilitates their work by removing obstacles and ensuring they have what they need to succeed
- **Product Managers**: Ensures the backlog is ready for planning and helps with prioritization discussions
- **Technical Lead**: Coordinates on technical blockers and process improvements
- **All team members**: Facilitates collaboration, resolves conflicts, and coaches on agile practices

### Example Scenario
During a sprint, a Scrum Master notices in the daily standup that developers are blocked waiting for an API specification. They immediately coordinate with the Technical Lead and external team to expedite the documentation. They track team velocity trends and bring data to a retrospective, facilitating a discussion that results in actionable improvements to the team's PR review process.

---

## UX/UI Designer

### Role Summary
UX/UI Designers create intuitive, accessible, and visually appealing user experiences. They advocate for users throughout the product development lifecycle, designing interfaces that meet both user needs and business objectives.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Design user interfaces that are accessible and responsive
- Maintain design systems and component libraries
- Advocate for usability, accessibility, and inclusive design
- Collaborate on information architecture and user flows
- Validate designs with users and iterate based on feedback

### Goals
- Deliver user-centered designs that solve real user problems
- Ensure consistent, accessible user experiences across products
- Reduce development rework through validated designs
- Improve user satisfaction and engagement metrics

### Typical Communication
- Design mockups, prototypes, and interactive demos
- User research reports and usability testing summaries
- Design system documentation and component specifications
- Design review presentations and critique sessions

### Interactions with Other Roles
- **Product Managers**: Collaborates on feature definition, user needs, and success metrics; validates designs align with product strategy
- **Developers**: Provides design specifications, assets, and implementation guidance; reviews implemented features for design fidelity
- **Business Analyst**: Ensures designs meet documented requirements and business processes
- **Technical Lead**: Discusses technical feasibility and performance implications of design decisions
- **Support/Customer Success**: Gathers user feedback and pain points to inform design improvements
- **Stakeholders**: Presents designs for feedback and alignment

### Example Scenario
A UX/UI Designer conducts user interviews to understand pain points with the current dashboard. They create wireframes and conduct usability testing with users, iterating on the design based on feedback. After validation, they create high-fidelity mockups and a design specification document. During development, they review implementation with developers, provide feedback on spacing and interactions, and validate the final feature matches the intended design before release.

---

## Support / Customer Success

### Role Summary
Support and Customer Success teams are the voice of the customer, providing frontline assistance while collecting valuable insights that drive product improvement. They ensure customers achieve their desired outcomes and serve as a critical feedback loop for the product and engineering teams.

### Responsibilities
- Provide technical support and troubleshooting assistance to users
- Aggregate and analyze user feedback and feature requests
- Track and escalate bugs and issues to engineering
- Monitor impact of released features on user experience
- Document common issues and create knowledge base articles
- Conduct customer onboarding and training
- Measure and improve customer satisfaction and retention metrics

### Goals
- Achieve high customer satisfaction and resolution rates
- Reduce time-to-resolution for customer issues
- Provide actionable product feedback to drive improvements
- Ensure successful customer adoption and ongoing value realization

### Typical Communication
- Support tickets and issue escalations
- Customer feedback summaries and feature request logs
- Release impact reports and user adoption metrics
- Knowledge base articles and customer communications

### Interactions with Other Roles
- **Product Managers**: Provides user feedback, feature requests, and insights into customer needs and pain points
- **Developers**: Reports bugs, provides reproduction steps, and validates fixes in production
- **QA/Testers**: Collaborates on testing scenarios based on real-world usage patterns
- **Project Managers**: Communicates customer impact of delays or issues, helps prioritize critical fixes
- **Business Analyst**: Provides real-world use cases and edge cases discovered through customer interactions
- **UX/UI Designer**: Shares usability feedback and customer pain points to inform design decisions

### Example Scenario
After a new feature release, a Customer Success Manager notices an increase in support tickets about a confusing workflow. They aggregate the feedback with specific examples and user quotes, then meet with the Product Manager and UX Designer to discuss the issue. They provide detailed reproduction steps to the development team and help validate the fix with customers. After the improvement is deployed, they create a knowledge base article and proactively communicate the enhancement to affected customers.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

**Related**: This document was expanded based on [Issue #4: Adding more personas and roles to the project management processes](https://github.com/JaimeBudi/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to improve clarity of responsibilities and cross-functional collaboration.


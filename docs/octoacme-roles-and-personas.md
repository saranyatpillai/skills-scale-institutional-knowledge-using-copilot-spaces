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

## QA/Testing Specialist

### Role Summary
QA/Testing Specialists own the quality strategy, test planning, and acceptance validation. They collaborate with developers and product leads to ensure features meet acceptance criteria and quality standards before release.

### Responsibilities
- Develop and maintain test plans aligned with acceptance criteria
- Execute manual and automated testing across feature areas
- Identify and document defects with clear reproduction steps
- Participate in Definition of Done reviews and acceptance sign-off
- Contribute to test automation and CI/CD quality gates
- Advise on testability during design and development phases

### Goals
- Ensure features meet acceptance criteria before production release
- Minimize defects reaching production
- Maintain high test coverage and execution velocity
- Build confidence in release quality

### Typical Communication
- Sprint planning and backlog refinement
- Test case reviews with product and development
- Defect reports and regression testing updates
- Pre-release sign-off and smoke test execution

### Interaction with Other Roles
- **Developers**: Collaborate on test case design; developers ensure automated tests pass before requesting QA review
- **Product Managers**: Align on acceptance criteria and feature scope before testing begins
- **Project Managers**: Participate in scheduling to ensure adequate test time in sprint/milestone planning
- **Technical Lead**: Consult on testing strategy for complex technical components

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, make architectural decisions, and mitigate technical risks. They mentor developers, guide design reviews, and ensure solutions align with long-term technical vision.

### Responsibilities
- Define technical approach and architecture for projects
- Conduct technical design reviews and code architecture validation
- Mentor developers and guide technical problem-solving
- Identify and escalate technical risks and debt items
- Make trade-off decisions between performance, maintainability, and delivery speed
- Participate in spike investigations for technical unknowns

### Goals
- Ensure solutions are scalable, maintainable, and aligned with technical vision
- Reduce technical debt and mitigate long-term technical risk
- Accelerate team delivery through technical guidance and unblocking
- Build a culture of technical excellence

### Typical Communication
- Design review meetings with developers and PMs
- Architecture documentation and decision logs
- Technical spike reports and risk assessments
- Code review comments on architectural decisions

### Interaction with Other Roles
- **Developers**: Provide technical direction; developers seek guidance on approach and design decisions
- **Product Managers**: Advise on technical feasibility and trade-offs; help scope work for technical reality
- **Project Managers**: Escalate technical risks and estimate effort impact
- **QA/Testing Specialist**: Advise on testing strategy for complex components

---

## Sponsor/Executive Stakeholder

### Role Summary
Sponsors provide executive oversight, business context, and decision authority. They remove organizational blockers, align projects with strategic goals, and represent the business perspective.

### Responsibilities
- Set business context and strategic alignment for projects
- Make high-level go/no-go and scope decisions
- Secure budget and resources for project delivery
- Remove organizational blockers and dependencies
- Provide executive escalation path for critical decisions
- Receive and act on status updates and risk escalations

### Goals
- Ensure projects deliver measurable business value
- Align delivery with strategic priorities and budgets
- Remove barriers to execution
- Maintain executive visibility into critical risks

### Typical Communication
- Monthly stakeholder briefings
- Escalation path for business-impacting risks
- High-level status and milestone updates
- Resource and budget decisions

### Interaction with Other Roles
- **Project Managers**: Receive escalations and provide resource/scope decisions; get regular status updates
- **Product Managers**: Collaborate on strategic alignment and success metrics
- **Developers**: May provide input on critical technical blockers requiring executive intervention

---

## Cross-Functional Coordinator (Integrator)

### Role Summary
Cross-Functional Coordinators manage dependencies across multiple teams, systems, and projects. They ensure smooth integration and alignment when work spans organizational boundaries.

### Responsibilities
- Identify and track cross-team dependencies
- Facilitate dependency planning during project planning phase
- Coordinate integration testing and handoffs
- Escalate dependency risks and schedule conflicts
- Maintain communication between teams on integration status
- Resolve resource conflicts and scheduling issues

### Goals
- Minimize integration delays and rework
- Ensure timely handoffs between teams
- Maintain transparency across team boundaries
- Reduce duplicate work and communication gaps

### Typical Communication
- Cross-team dependency planning meetings
- Weekly integration status checks
- Escalation of scheduling conflicts or blocker dependencies
- Integration test coordination

### Interaction with Other Roles
- **Project Managers**: Coordinate schedules and manage cross-team dependencies
- **Developers**: Provide integration testing coordination; align on API contracts and handoff criteria
- **Technical Leads**: Advise on integration architecture and contract definitions
- **QA/Testing Specialist**: Coordinate integration and end-to-end testing across teams

---

## Scrum Master/Delivery Facilitator

### Role Summary
Scrum Masters facilitate agile ceremonies, remove impediments, and shield the team from distractions. They ensure the team follows agreed-upon processes and continuously improves. (Optional based on team structure)

### Responsibilities
- Facilitate daily standups, planning, reviews, and retrospectives
- Identify and help resolve team impediments
- Protect team focus time and shield from distractions
- Track and report on process metrics (velocity, cycle time)
- Coach team on agile practices and continuous improvement
- Maintain project board and artifact organization

### Goals
- Maximize team productivity and focus
- Accelerate delivery through process efficiency
- Build a culture of continuous improvement
- Remove obstacles to team success

### Typical Communication
- Daily standup facilitation
- Ceremony scheduling and execution
- Impediment tracking and escalation
- Retrospective action item follow-up

### Interaction with Other Roles
- **Project Managers**: Coordinate on scheduling; escalate impediments and resource conflicts
- **Developers**: Facilitate ceremonies and remove blockers
- **All roles**: Ensure process adherence and continuous improvement feedback

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

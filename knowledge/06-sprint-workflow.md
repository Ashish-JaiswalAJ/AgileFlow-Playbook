# Sprint Workflow & Planning

## 1. Purpose

This document defines how AgileFlow should understand and support the Sprint workflow, including:

- Sprint
- Sprint Goal
- Sprint Planning
- Sprint Backlog
- Sprint execution
- Daily Scrum
- adapting the Sprint Backlog
- scope changes
- Increment creation
- Sprint Review
- Sprint Retrospective
- cancellation
- capacity planning
- velocity and burndown as optional practices

The central rule is:

> Scrum defines the Sprint and its events, artifacts, and commitments, but does not prescribe one complete project-management workflow.

Formal Scrum concepts must remain distinct from complementary practices.

---

# 2. Sprint

A Sprint is a fixed-length event of one month or less during which a usable and valuable Increment is created.

A new Sprint starts immediately after the previous Sprint concludes.

Classification: [SCRUM]

During a Sprint:

- the Sprint Goal should remain protected
- quality must not decrease
- the Product Backlog can be refined as needed
- scope may be clarified and renegotiated with the Product Owner as more is learned
- the Sprint Backlog can be adapted

---

# 3. Sprint Length

Scrum allows Sprints of one month or less.

Scrum does not require:

- two-week Sprints
- one-week Sprints
- any other specific Sprint duration below the one-month maximum

A team can choose a Sprint length appropriate to its context.

Classification:

- Sprint maximum of one month: [SCRUM]
- Specific Sprint duration: [TEAM] / [PRACTICE]

### Agent Rule

If a user says:

> "Our team uses two-week Sprints."

Treat this as a team convention.

Do not state:

> "Scrum requires two-week Sprints."

---

# 4. Sprint Goal

The Sprint Goal is the single objective for the Sprint.

It creates coherence and focus for the work selected during Sprint Planning.

The Sprint Goal is created during Sprint Planning and added to the Sprint Backlog.

Classification: [SCRUM]

### Agent Guidance

When helping create a Sprint Goal:

1. Identify the desired outcome.
2. Connect it to product value or the Product Goal where possible.
3. Keep the objective coherent.
4. Avoid creating a list of unrelated tasks as the Sprint Goal.
5. Preserve the user's actual intent.
6. Identify assumptions when information is missing.

---

# 5. Sprint Planning

Sprint Planning initiates the Sprint.

It addresses three topics:

1. Why is this Sprint valuable?
2. What can be Done in the Sprint?
3. How will the chosen work get done?

Classification: [SCRUM]

---

# 6. Sprint Planning — Why

The Product Owner proposes how the product could increase its value and utility in the current Sprint.

The whole Scrum Team collaborates to define a Sprint Goal that communicates why the Sprint is valuable.

The Sprint Goal should provide a coherent objective for the Sprint.

Classification: [SCRUM]

---

# 7. Sprint Planning — What

Developers select Product Backlog Items for the Sprint.

Selection considers:

- the Sprint Goal
- the Developers' understanding of the work
- what they believe can be accomplished

The resulting selected work becomes part of the Sprint Backlog.

Classification: [SCRUM]

### Important boundary

The Product Owner does not simply assign a fixed list of tasks to Developers.

Developers select the Product Backlog Items they believe can be accomplished while pursuing the Sprint Goal.

---

# 8. Sprint Planning — How

Developers plan the work necessary to create an Increment that meets the Definition of Done.

The resulting plan becomes part of the Sprint Backlog.

The plan can be adapted as more is learned during the Sprint.

Classification: [SCRUM]

---

# 9. Sprint Backlog

The Sprint Backlog consists of:

- Sprint Goal
- selected Product Backlog Items
- actionable plan for delivering the Increment

It is a plan by and for the Developers.

Classification: [SCRUM]

The Sprint Backlog should provide a real-time picture of the work Developers plan to accomplish during the Sprint.

---

# 10. Sprint Backlog Is Not Frozen

A common misconception is:

> "The Sprint Backlog cannot change after Sprint Planning."

Correction:

The Sprint Backlog can be adapted throughout the Sprint as more is learned.

Developers update the plan as necessary while maintaining focus on the Sprint Goal.

Classification: [SCRUM]

### Important boundary

Adaptation does not mean uncontrolled scope expansion.

Changes should be considered in relation to the Sprint Goal and the ability to maintain quality.

---

# 11. Sprint Execution

During Sprint execution, the Scrum Team works toward the Sprint Goal and creates a usable Increment.

AgileFlow should encourage:

- transparency
- collaboration
- continuous refinement
- quality throughout development
- inspection of progress
- adaptation based on new information

The exact development workflow is not prescribed by Scrum.

Teams may use additional engineering and project-management practices.

Classification:

- Scrum Sprint: [SCRUM]
- Specific development workflow: [PRACTICE] / [TEAM]

---

# 12. Daily Scrum

The Daily Scrum is a 15-minute event for the Developers.

Its purpose is to inspect progress toward the Sprint Goal and adapt the Sprint Backlog as necessary.

Classification: [SCRUM]

Developers determine the structure and techniques used.

### Important boundary

The Daily Scrum is not required to use the traditional three questions:

- What did I do yesterday?
- What will I do today?
- What is blocking me?

Those questions are one possible technique.

Classification of three-question format: [PRACTICE]

---

# 13. Daily Scrum Is Not a Status Report

A common misuse is treating the Daily Scrum as a report from Developers to the Product Owner, Scrum Master, or manager.

The purpose is to inspect progress toward the Sprint Goal and adapt the plan.

Developers should use the event to coordinate and adjust their work.

Classification: [SCRUM]

---

# 14. Scope Changes During a Sprint

Requirements and understanding can change during a Sprint.

The team can clarify and renegotiate scope with the Product Owner as more is learned.

The Sprint Goal provides the focus that should be protected.

### Agent Guidance

When a user asks:

> "Can we add new work during a Sprint?"

Do not answer with a simple universal "yes" or "no."

Instead explain:

- the Sprint Backlog can change
- new information can change the plan
- scope can be clarified or renegotiated
- the Sprint Goal should remain protected
- quality should not decrease

Classification: [SCRUM]

---

# 15. Sprint Goal vs Scope

The Sprint Goal and the exact selected work are different concepts.

The Sprint Goal provides the objective.

The Sprint Backlog contains the selected work and plan for achieving it.

As more is learned, the plan or scope can change while preserving the Sprint Goal.

Example:

Initial plan:

> Implement online registration and status viewing.

During the Sprint, the team discovers that one implementation approach is unnecessary.

The plan can change while the Sprint Goal remains the same.

AgileFlow should focus on whether the goal remains achievable rather than treating every task change as a problem.

Classification: [SCRUM]

---

# 16. Sprint Cancellation

A Sprint can be cancelled if the Sprint Goal becomes obsolete.

The Product Owner has the authority to cancel the Sprint.

Sprint cancellation should not be presented as a normal mechanism for handling every scope change.

Classification: [SCRUM]

### Agent Guidance

If a user asks whether a Sprint can be cancelled because requirements changed, AgileFlow should ask whether the Sprint Goal has become obsolete.

Do not automatically recommend cancellation merely because individual requirements changed.

---

# 17. Increment During the Sprint

Multiple Increments may be created during a Sprint.

An Increment must:

- be usable
- meet the Definition of Done
- contribute toward the Product Goal

Work that does not meet the Definition of Done is not part of the Increment.

Classification: [SCRUM]

### Core relationship

```text
Work satisfies Definition of Done
        ↓
Usable product outcome
        ↓
Increment
````

---

# 18. Every Sprint Does Not Automatically Mean Production Release

Scrum requires a usable Increment, but it does not state that every Sprint must result in a production deployment.

Whether and when an Increment is released depends on product and organizational context.

Classification:

* Usable Increment: [SCRUM]
* Production deployment schedule: [TEAM] / [PRACTICE]

AgileFlow should not tell users that Scrum requires production deployment after every Sprint.

---

# 19. Sprint Review

The Sprint Review occurs at the end of the Sprint to inspect the outcome and determine future adaptations.

The Scrum Team and stakeholders collaborate about:

* what was accomplished
* what changed in the product environment
* what should be done next
* possible Product Backlog adaptations

Classification: [SCRUM]

### Important boundary

The Sprint Review is broader than a demo.

A demonstration can be part of the Review, but the Review is an inspection and adaptation opportunity involving relevant stakeholders.

---

# 20. Sprint Retrospective

The Sprint Retrospective is an opportunity for the Scrum Team to inspect how the Sprint went and identify ways to increase quality and effectiveness.

The team may inspect:

* individuals and interactions
* processes
* tools
* Definition of Done
* other relevant aspects of its way of working

The team identifies the most useful changes.

Classification: [SCRUM]

### Important boundary

A Retrospective should not become:

* a blame session
* a meeting with no improvement action
* a generic discussion without evidence

---

# 21. Capacity Planning

Capacity planning is a common practice that may help a team understand how much work it can reasonably take on.

It may consider:

* team availability
* holidays
* planned leave
* other commitments
* known constraints
* historical information

Classification: [PRACTICE]

Scrum does not prescribe a specific capacity-planning formula.

AgileFlow should not present capacity calculations as exact predictions.

---

# 22. Velocity

Velocity is a commonly used metric based on the amount of estimated work a team completes over time.

Classification: [OPTIONAL]

Velocity can sometimes provide historical information for planning.

However:

* Scrum does not require velocity.
* Velocity is not a formal Scrum artifact.
* Velocity is not a universal measure of productivity.
* Individual developer velocity should not be used as a performance metric.
* Teams should not be forced to increase velocity as a goal.

### Agent Rule

If a user asks:

> "How do I increase my developer's velocity?"

AgileFlow should avoid treating individual velocity as a performance target.

Instead, inspect:

* quality
* value delivered
* workflow
* bottlenecks
* dependencies
* work size
* interruptions
* technical constraints

Classification: [OPTIONAL] / [PRACTICE]

---

# 23. Burndown Charts

Burndown charts are a common Agile project-management visualization.

They can show remaining work over time.

Classification: [OPTIONAL]

Scrum does not require burndown charts.

A team may use them if they provide useful transparency.

AgileFlow should not claim that a Scrum Team must maintain a burndown chart.

---

# 24. Task Breakdown

Breaking Product Backlog Items into smaller implementation tasks can help Developers plan their work.

Classification: [PRACTICE]

Scrum does not require a particular task structure.

Developers decide how the selected work will be accomplished.

Do not require:

* frontend task
* backend task
* testing task
* documentation task

for every PBI unless the team's context requires them.

---

# 25. Task Assignment

A common misconception is:

> "The Product Owner assigns each task to a Developer."

Correction:

Developers are self-managing and decide how the work gets done.

Scrum does not prescribe individual task assignment by the Product Owner.

Classification: [SCRUM]

A team may use coordination practices for work distribution, but these are team practices rather than a universal Scrum requirement.

Classification: [TEAM] / [PRACTICE]

---

# 26. Sprint Planning Workflow for AgileFlow

When a user asks AgileFlow to help plan a Sprint:

### Step 1 — Understand the Product Goal

If known, establish how the Sprint contributes toward it.

### Step 2 — Identify the Sprint objective

Determine what valuable outcome the Sprint should pursue.

### Step 3 — Draft the Sprint Goal

Create one coherent objective.

### Step 4 — Examine candidate PBIs

Consider:

* relevance to Sprint Goal
* understanding
* size
* dependencies
* known constraints

### Step 5 — Select work

Developers select the work they believe can be accomplished.

### Step 6 — Create the Sprint Backlog

Include:

* Sprint Goal
* selected PBIs
* actionable plan

### Step 7 — Identify uncertainty

Clearly state assumptions and unresolved questions.

### Step 8 — Plan execution

Break work down as useful without imposing a universal task structure.

### Step 9 — Establish inspection points

Use the Daily Scrum and other appropriate activities to inspect progress.

### Step 10 — Adapt

Update the Sprint Backlog as new information appears while protecting the Sprint Goal and quality.

---

# 27. Sprint Troubleshooting

When a user says:

> "Our Sprint keeps failing."

AgileFlow should not immediately identify one cause.

Use:

```text
Observation
    ↓
Possible interpretations
    ↓
Evidence
    ↓
Potential adaptation
```

### Example

Observation:

> Several PBIs are unfinished at the end of the Sprint.

Possible causes:

* items may be too large
* requirements may be unclear
* unexpected technical complexity
* dependencies
* interruptions
* insufficient understanding
* quality problems

These are possibilities, not established facts.

AgileFlow should ask for evidence before concluding which cause applies.

---

# 28. When the Sprint Goal Is at Risk

If the Sprint Goal appears unlikely to be achieved, AgileFlow should help inspect:

* current progress
* remaining work
* changed requirements
* dependencies
* blockers
* technical uncertainty
* quality issues
* whether the selected scope can be adapted

Possible responses may include:

* adapt the Sprint Backlog
* renegotiate scope while preserving the Sprint Goal
* remove lower-value scope where appropriate
* address impediments
* clarify requirements
* split or simplify work

Do not automatically recommend Sprint cancellation.

Cancellation is relevant when the Sprint Goal becomes obsolete.

Classification: [SCRUM] / [PRACTICE]

---

# 29. Sprint Review and Adaptation

When helping prepare a Sprint Review, AgileFlow should focus on:

* the Sprint outcome
* what changed
* stakeholder feedback
* current product context
* Product Backlog implications
* possible future adaptations

Do not reduce the Review to:

> "Show the completed features."

The purpose is broader inspection and collaboration.

Classification: [SCRUM]

---

# 30. Sprint Retrospective Workflow

When helping conduct a Retrospective:

1. Establish what happened during the Sprint.
2. Inspect relevant evidence.
3. Discuss what helped effectiveness.
4. Discuss what reduced effectiveness.
5. Identify improvement opportunities.
6. Select useful improvement actions.
7. Decide how improvements will be incorporated into future work.
8. Avoid blame and unsupported assumptions.

Classification: [SCRUM]

---

# 31. Common Sprint Misconceptions

### Misconception 1

> "A Sprint must last two weeks."

Correction:

Scrum defines a Sprint as one month or less. A specific duration is a team choice.

---

### Misconception 2

> "The Sprint Backlog is frozen after Sprint Planning."

Correction:

The Sprint Backlog can be adapted throughout the Sprint.

---

### Misconception 3

> "The Product Owner assigns tasks to Developers."

Correction:

Developers are self-managing and decide how the work gets done.

---

### Misconception 4

> "The Daily Scrum must use three questions."

Correction:

The three questions are one possible technique. Scrum defines the event's purpose, not that specific format.

---

### Misconception 5

> "The Daily Scrum is a status meeting for management."

Correction:

It is a 15-minute event for Developers to inspect progress toward the Sprint Goal and adapt the Sprint Backlog.

---

### Misconception 6

> "The Sprint Review is just a demo."

Correction:

The Review is an opportunity to inspect the Sprint outcome and collaborate on future adaptations.

---

### Misconception 7

> "The Sprint Retrospective is where the team identifies who caused problems."

Correction:

The Retrospective focuses on improving quality and effectiveness, not assigning blame.

---

### Misconception 8

> "Every Sprint must end with a production deployment."

Correction:

Scrum requires a usable Increment that meets the Definition of Done, but it does not universally require production deployment every Sprint.

---

### Misconception 9

> "If a Sprint is going badly, cancel it."

Correction:

Sprint cancellation is relevant when the Sprint Goal becomes obsolete. Problems or changing scope do not automatically make cancellation appropriate.

---

### Misconception 10

> "Velocity must increase every Sprint."

Correction:

Velocity is an optional practice and should not be treated as a universal performance target.

---

# 32. Classification Reference

| Concept                            | Classification      |
| ---------------------------------- | ------------------- |
| Sprint                             | [SCRUM]             |
| Sprint Goal                        | [SCRUM]             |
| Sprint Planning                    | [SCRUM]             |
| Sprint Backlog                     | [SCRUM]             |
| Daily Scrum                        | [SCRUM]             |
| Sprint Review                      | [SCRUM]             |
| Sprint Retrospective               | [SCRUM]             |
| Increment                          | [SCRUM]             |
| Task breakdown                     | [PRACTICE]          |
| Task assignment method             | [TEAM] / [PRACTICE] |
| Capacity planning                  | [PRACTICE]          |
| Velocity                           | [OPTIONAL]          |
| Burndown chart                     | [OPTIONAL]          |
| Two-week Sprint                    | [TEAM] / [PRACTICE] |
| Three Daily Scrum questions        | [PRACTICE]          |
| Production deployment every Sprint | [TEAM] / [PRACTICE] |

---

# 33. Core Sprint Rule

> A Sprint is a fixed-length container for Scrum events and work toward a Sprint Goal. The Sprint Backlog is an evolving plan that can be adapted while protecting the Sprint Goal and quality.

AgileFlow must:

* preserve the Sprint Goal
* distinguish Sprint Backlog from Product Backlog
* recognize that the Sprint Backlog can change
* respect Developer self-management
* distinguish formal Scrum events from optional team practices
* avoid imposing two-week Sprints
* avoid imposing the three Daily Scrum questions
* avoid treating velocity as a performance target
* avoid treating burndown charts as mandatory
* avoid treating production deployment as a universal Scrum requirement
* use evidence when troubleshooting Sprint problems
* avoid automatically recommending Sprint cancellation

### Final principle

> Sprint execution is empirical: inspect progress and outcomes, adapt the plan when necessary, and maintain focus on the Sprint Goal and product quality.

**Next: `07-estimation.md`.**

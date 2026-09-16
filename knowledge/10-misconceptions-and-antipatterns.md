# Agile & Scrum Misconceptions and Antipatterns

## 1. Purpose

This document helps AgileFlow identify and explain common misunderstandings about Agile and Scrum.

It covers:

- Agile misconceptions
- Scrum misconceptions
- mandatory vs optional practices
- common workflow mistakes
- misuse of artifacts and events
- estimation misconceptions
- quality misconceptions
- backlog misconceptions
- Sprint misconceptions
- inspection and adaptation problems
- troubleshooting guidance

The central rule is:

> AgileFlow should correct misconceptions by explaining the relevant distinction rather than simply labeling the user's approach as wrong.

---

# 2. Source Boundary

AgileFlow must distinguish between:

- formal Scrum requirements
- Agile values and principles
- common Agile practices
- optional techniques
- academic/course requirements
- team-specific conventions
- unknown or unsupported claims

Classification tags:

```text
[SCRUM]
[AGILE]
[PRACTICE]
[OPTIONAL]
[COURSE]
[TEAM]
[UNKNOWN]
````

A commonly used practice must not automatically be presented as a Scrum requirement.

---

# 3. Core Anti-Confusion Rule

AgileFlow should ask:

> "Is this actually required by Scrum, or is it a commonly used practice?"

This distinction should be maintained throughout answers.

Scrum does not automatically require:

* user stories
* acceptance criteria
* Definition of Ready
* story points
* Planning Poker
* Fibonacci estimation
* velocity
* burndown charts
* Jira
* two-week Sprints
* the three Daily Scrum questions
* TDD
* Continuous Integration
* a specific testing framework
* a specific backlog template

These may be useful practices, but they should be classified appropriately.

---

# 4. Agile Is Not One Fixed Process

### Misconception

> "Agile means following a fixed set of steps."

Correction:

Agile is based on values and principles. It does not prescribe one universal workflow.

Different teams may organize their work differently while applying Agile principles.

Classification:

* Agile values/principles: [AGILE]
* Specific workflow: [TEAM] / [PRACTICE]

---

# 5. Agile Means No Planning

### Misconception

> "Agile teams do not plan."

Correction:

Agile teams plan, but plans can evolve as new information becomes available.

Planning and adaptation can coexist.

Classification: [AGILE] / [PRACTICE]

---

# 6. Agile Means No Documentation

### Misconception

> "Agile says documentation is unnecessary."

Correction:

Agile does not say that documentation has no value.

The Agile Manifesto states a preference for working software over comprehensive documentation, while still recognizing value in the item on the right.

The appropriate level of documentation depends on context.

Classification: [AGILE]

AgileFlow should not recommend removing necessary documentation merely to appear Agile.

---

# 7. Scrum and Agile Are the Same Thing

### Misconception

> "Scrum is another name for Agile."

Correction:

Agile is broader than Scrum.

Agile describes values and principles.

Scrum is a framework for addressing complex problems and generating value through adaptive solutions.

Classification:

* Agile: [AGILE]
* Scrum: [SCRUM]

---

# 8. Scrum Requires User Stories

### Misconception

> "Every Scrum Product Backlog Item must be a user story."

Correction:

User stories are a commonly used requirements practice.

Scrum does not require the user-story format.

Product Backlog Items can be represented in different ways.

Classification:

* Product Backlog Items: [SCRUM]
* User stories: [PRACTICE]

---

# 9. Scrum Requires Acceptance Criteria

### Misconception

> "Acceptance criteria are mandatory Scrum artifacts."

Correction:

Acceptance criteria are commonly used to describe conditions associated with a particular Product Backlog Item.

They are not a separate mandatory Scrum artifact.

Classification: [PRACTICE]

---

# 10. Definition of Ready Is Required

### Misconception

> "A PBI cannot enter a Sprint unless it passes Definition of Ready."

Correction:

Definition of Ready is a commonly used team practice.

Scrum does not require a Definition of Ready.

Classification: [PRACTICE]

A team may use readiness criteria if useful.

---

# 11. Definition of Ready and Definition of Done Are the Same

### Misconception

> "Ready and Done are two versions of the same Scrum requirement."

Correction:

They serve different purposes.

### Definition of Ready

A team practice describing conditions that indicate a PBI is sufficiently prepared for development or selection.

Classification: [PRACTICE]

### Definition of Done

The quality state required for work to be part of the Increment.

Classification: [SCRUM]

---

# 12. Story Points Are Required

### Misconception

> "Every Scrum Team must estimate using story points."

Correction:

Story points are an optional relative estimation technique.

Scrum does not require story points.

Classification: [OPTIONAL] / [PRACTICE]

---

# 13. Fibonacci Numbers Are Required

### Misconception

> "Agile estimation must use 1, 2, 3, 5, 8, 13."

Correction:

Fibonacci-style scales are one possible estimation convention.

They are not required by Scrum.

Classification: [OPTIONAL] / [TEAM]

---

# 14. Planning Poker Is Required

### Misconception

> "Scrum estimation means Planning Poker."

Correction:

Planning Poker is a collaborative estimation technique.

It is optional.

Classification: [OPTIONAL]

---

# 15. Velocity Is Required

### Misconception

> "A Scrum Team must calculate velocity."

Correction:

Velocity is an optional Agile practice.

Scrum does not require velocity.

Classification: [OPTIONAL]

---

# 16. Velocity Measures Individual Productivity

### Misconception

> "The Developer with the highest story-point output is the best Developer."

Correction:

Story points are relative and team-specific.

Velocity is generally a team-level historical measure when used.

Individual story-point totals should not be treated as a universal measure of individual productivity.

Classification: [OPTIONAL] / [PRACTICE]

---

# 17. Velocity Must Increase Every Sprint

### Misconception

> "A healthy team must increase velocity every Sprint."

Correction:

Velocity is optional and is not a universal performance target.

Changes in velocity can result from many factors.

AgileFlow should inspect context rather than assuming that an increase is always improvement.

---

# 18. Burndown Is Required

### Misconception

> "Every Scrum Team needs a Sprint burndown chart."

Correction:

Burndown charts are optional visualization practices.

Scrum does not require them.

Classification: [OPTIONAL]

---

# 19. Scrum Requires Jira

### Misconception

> "You cannot do Scrum without Jira."

Correction:

Scrum does not require Jira or any particular software tool.

A team may use Jira or another tool according to its context.

Classification:

* Scrum: [SCRUM]
* Jira: [TEAM] / [PRACTICE]

---

# 20. Scrum Requires Two-Week Sprints

### Misconception

> "A Sprint must be two weeks."

Correction:

A Sprint is fixed-length and is one month or less.

The exact duration is a team decision.

Classification:

* Sprint: [SCRUM]
* Two-week duration: [TEAM] / [PRACTICE]

---

# 21. Daily Scrum Requires Three Questions

### Misconception

> "The Daily Scrum must always use the three traditional questions."

Correction:

The three-question format is one possible technique.

The Daily Scrum's purpose is to inspect progress toward the Sprint Goal and adapt the Sprint Backlog as necessary.

Classification:

* Daily Scrum: [SCRUM]
* Three-question format: [PRACTICE]

---

# 22. Daily Scrum Is a Manager Status Meeting

### Misconception

> "Developers report their status to the manager during the Daily Scrum."

Correction:

The Daily Scrum is a 15-minute event for Developers.

It focuses on progress toward the Sprint Goal and adapting the Sprint Backlog.

Classification: [SCRUM]

---

# 23. Product Owner Assigns Developer Tasks

### Misconception

> "The Product Owner should distribute every task among Developers."

Correction:

Developers are self-managing and decide how the work gets done.

Specific task assignment approaches may exist within a team, but Scrum does not prescribe Product Owner assignment of individual Developer tasks.

Classification:

* Developer self-management: [SCRUM]
* Task assignment convention: [TEAM] / [PRACTICE]

---

# 24. Sprint Backlog Cannot Change

### Misconception

> "Once Sprint Planning ends, the Sprint Backlog is frozen."

Correction:

The Sprint Backlog can evolve during the Sprint.

Developers adapt the plan as more is learned while maintaining focus on the Sprint Goal.

Classification: [SCRUM]

---

# 25. Every New Requirement Must Be Rejected During a Sprint

### Misconception

> "Nothing can change once a Sprint begins."

Correction:

The Sprint Backlog can change.

Scope can be clarified and renegotiated with the Product Owner as more is learned.

The Sprint Goal should remain protected.

Classification: [SCRUM]

---

# 26. Every New Requirement Must Be Added Immediately

### Misconception

> "Agile means accepting every stakeholder request immediately."

Correction:

New information may lead to Product Backlog adaptation, but not every request automatically becomes selected Sprint work.

The Product Owner is accountable for Product Backlog management and ordering.

Classification: [SCRUM]

---

# 27. Sprint Review Is Just a Demo

### Misconception

> "Sprint Review means showing completed features."

Correction:

The Sprint Review is broader than a demonstration.

It is an opportunity to inspect the Sprint outcome and collaborate with stakeholders about future adaptations.

Classification: [SCRUM]

---

# 28. Sprint Retrospective Is a Blame Meeting

### Misconception

> "The Retrospective is where the team decides who caused problems."

Correction:

The Sprint Retrospective focuses on inspecting how the Sprint went and identifying ways to improve effectiveness and quality.

Classification: [SCRUM]

---

# 29. Sprint Goal and Sprint Backlog Are the Same

### Misconception

> "The Sprint Goal is simply the list of Sprint tasks."

Correction:

The Sprint Goal is the objective for the Sprint.

The Sprint Backlog contains:

* Sprint Goal
* selected Product Backlog Items
* actionable plan

Classification: [SCRUM]

---

# 30. Product Backlog and Sprint Backlog Are the Same

### Misconception

> "The Sprint Backlog is just a copy of the Product Backlog."

Correction:

The Product Backlog is the ordered, emergent list of work for the product.

The Sprint Backlog contains the Sprint Goal, selected Product Backlog Items, and the plan for delivering the Increment.

Classification: [SCRUM]

---

# 31. Product Backlog Is a Complete Fixed Requirement List

### Misconception

> "The Product Backlog must contain every requirement from the beginning."

Correction:

The Product Backlog is emergent.

As the product and environment are better understood, it can evolve.

Classification: [SCRUM]

---

# 32. Product Backlog Ordering Means Technical Priority Only

### Misconception

> "Backlog order should simply follow development difficulty."

Correction:

The Product Owner is accountable for Product Backlog ordering.

Ordering should support product value and the Product Goal rather than simply reflecting technical difficulty.

Classification: [SCRUM]

---

# 33. Smaller Items Are Always More Important

### Misconception

> "Small PBIs should always be implemented before large PBIs."

Correction:

Size and ordering are different concepts.

A small item is not automatically more valuable or higher priority than a large item.

Classification:

* Product Backlog ordering: [SCRUM]
* Sizing: [PRACTICE]

---

# 34. Large PBIs Are Automatically Bad

### Misconception

> "A large PBI means the team is doing Agile incorrectly."

Correction:

A large or poorly understood PBI may indicate an opportunity for refinement or splitting, but size alone does not establish that a team is failing.

AgileFlow should inspect:

* scope
* ambiguity
* dependencies
* complexity
* uncertainty

before recommending adaptation.

---

# 35. Coding Complete Means Done

### Misconception

> "The Developer finished coding, so the PBI is Done."

Correction:

Work is Done when it satisfies the Definition of Done.

Coding completion alone does not establish Done.

Classification: [SCRUM]

---

# 36. Testing Can Always Be Deferred

### Misconception

> "Testing can be skipped during the Sprint and completed later."

Correction:

If required testing is part of the Definition of Done and remains incomplete, the work does not meet the Definition of Done.

It is not part of the Increment.

Classification: [SCRUM]

---

# 37. Scrum Requires Unit Testing

### Misconception

> "Every Scrum project must use unit tests."

Correction:

Scrum does not prescribe a specific testing technique.

A team may include unit testing in its quality practices or Definition of Done.

Classification: [PRACTICE] / [TEAM]

---

# 38. Scrum Requires Code Review

### Misconception

> "Code review is a Scrum requirement."

Correction:

Code review is an engineering practice.

A team or organization may include it in its Definition of Done, but Scrum does not universally prescribe it.

Classification: [PRACTICE] / [TEAM]

---

# 39. Scrum Requires TDD

### Misconception

> "Test-Driven Development is mandatory in Scrum."

Correction:

TDD is an optional engineering practice.

Scrum does not prescribe TDD.

Classification: [OPTIONAL]

---

# 40. Scrum Requires Continuous Integration

### Misconception

> "Continuous Integration is mandatory for Scrum."

Correction:

Continuous Integration is a complementary engineering practice.

Scrum does not prescribe a particular technical implementation method.

Classification: [PRACTICE] / [OPTIONAL]

---

# 41. Every Sprint Must End With Production Deployment

### Misconception

> "Scrum requires a production release at the end of every Sprint."

Correction:

Scrum requires a usable Increment that meets the Definition of Done.

Production deployment is a product or organizational decision and is not universally required after every Sprint.

Classification:

* Usable Increment: [SCRUM]
* Production deployment: [TEAM] / [PRACTICE]

---

# 42. Increment Means Production Release

### Misconception

> "An Increment is the same thing as a production deployment."

Correction:

An Increment is a usable product outcome that meets the Definition of Done.

Release decisions are separate from the definition of an Increment.

Classification: [SCRUM]

---

# 43. Agile Means Change Everything Continuously

### Misconception

> "An Agile team should constantly change its process."

Correction:

Agile and Scrum support adaptation based on inspection and learning.

Change should have a reason and should be evaluated in context.

Uncontrolled change is not the same as empirical adaptation.

Classification: [AGILE] / [SCRUM]

---

# 44. More Ceremonies Mean More Agile

### Misconception

> "Adding more meetings makes the team more Agile."

Correction:

AgileFlow should not introduce ceremonies merely because they are commonly used.

Scrum defines specific events, while additional meetings and ceremonies are team practices.

The usefulness of an additional activity depends on context.

Classification: [PRACTICE] / [TEAM]

---

# 45. More Documentation Means Better Agile

### Misconception

> "A larger backlog document automatically means better requirements."

Correction:

Agile values useful outcomes and appropriate communication.

Documentation should serve a purpose rather than being produced solely for volume.

Classification: [AGILE] / [PRACTICE]

---

# 46. More Metrics Mean Better Management

### Misconception

> "The more Agile metrics a team tracks, the better it is managing the project."

Correction:

Metrics are tools for inspection, not automatic definitions of success.

Each metric should be interpreted in context.

Classification: [OPTIONAL] / [PRACTICE]

---

# 47. Antipattern: Treating Optional Practices as Scrum Law

### Pattern

A team takes a commonly used Agile technique and presents it as mandatory Scrum.

Examples:

```text
Story points → "required by Scrum"
Planning Poker → "required by Scrum"
Velocity → "required by Scrum"
Jira → "required by Scrum"
Two-week Sprint → "required by Scrum"
```

### AgileFlow Response

Identify the actual Scrum concept and classify the additional technique.

Use:

```text
Formal Scrum requirement
        +
Complementary practice
```

rather than combining them into one rule.

---

# 48. Antipattern: Process Over Outcome

### Pattern

The team focuses heavily on:

* completing ceremonies
* updating templates
* maintaining metrics
* moving cards

while losing focus on product value and the Sprint Goal.

### AgileFlow Response

Redirect attention toward:

* Product Goal
* Sprint Goal
* valuable outcomes
* usable Increment
* quality
* inspection
* adaptation

Do not automatically add more process.

---

# 49. Antipattern: Artificially Inflating Estimates

### Pattern

A team increases story-point values to make velocity appear higher.

### Problem

The metric no longer represents a consistent relative sizing system.

### AgileFlow Response

Explain that changing estimates merely to increase velocity does not establish an actual increase in delivered value or productivity.

Classification: [PRACTICE]

---

# 50. Antipattern: Treating Velocity as a Target

### Pattern

Management tells a team:

> "Your velocity must increase next Sprint."

### AgileFlow Response

Explain that velocity is optional and historical when used.

Inspect the actual product and workflow outcomes instead of treating velocity as a universal target.

Do not use individual velocity to rank Developers.

---

# 51. Antipattern: Marking Incomplete Work as Done

### Pattern

A team marks work Done even though it does not satisfy the Definition of Done.

### AgileFlow Response

Explain:

```text
Does not meet DoD
      ↓
Not Done
      ↓
Not part of Increment
```

Transparency should be preserved.

Classification: [SCRUM]

---

# 52. Antipattern: Hiding Problems Until the Sprint Ends

### Pattern

The team notices a problem but waits until the Sprint Review to mention it.

### AgileFlow Response

Encourage earlier inspection and adaptation.

The Scrum framework relies on frequent inspection rather than intentionally hiding emerging problems.

Classification: [SCRUM]

---

# 53. Antipattern: Blaming Individuals for System Problems

### Pattern

A missed Sprint Goal is automatically attributed to one Developer.

### AgileFlow Response

Start with observable evidence.

Inspect:

* requirements
* scope
* dependencies
* complexity
* interruptions
* quality
* workflow
* team coordination

Do not infer individual fault without evidence.

---

# 54. Antipattern: Copying Another Team's Process

### Pattern

A team adopts another team's:

* Sprint duration
* story-point scale
* ceremonies
* templates
* metrics
* Definition of Done

without considering its own context.

### AgileFlow Response

Identify which elements are formal Scrum requirements and which are team-specific practices.

A team's local convention should not automatically become a universal rule.

---

# 55. Antipattern: Tool-Driven Scrum

### Pattern

The team assumes:

> "If our Jira board is updated, we are doing Scrum correctly."

### AgileFlow Response

A tool can support transparency, but using a tool does not establish that Scrum is being applied effectively.

Inspect:

* goals
* artifacts
* quality
* outcomes
* collaboration
* inspection
* adaptation

Classification: [PRACTICE]

---

# 56. Antipattern: Ceremony Compliance

### Pattern

The team focuses on technically holding every meeting without understanding its purpose.

Example:

> "We had the Daily Scrum, so we inspected progress."

But the event was only a management status report.

### AgileFlow Response

Explain the purpose of the event rather than treating attendance as proof of effective Scrum.

---

# 57. Antipattern: Template Compliance

### Pattern

A team assumes:

> "If the Product Backlog follows this template, it is correct."

### AgileFlow Response

A template is a practice.

AgileFlow should evaluate whether the backlog is understandable, ordered, useful, and aligned with the relevant product goals rather than treating a particular template as mandatory.

Classification: [PRACTICE]

---

# 58. Antipattern: Inventing Missing Requirements

### Pattern

A user gives an incomplete requirement and asks AgileFlow to create a complete specification.

### AgileFlow Response

AgileFlow should:

1. preserve the known intent
2. identify missing information
3. label assumptions
4. ask clarifying questions when necessary
5. avoid silently inventing business rules

Classification: [UNKNOWN] where information is not established.

---

# 59. Antipattern: Treating Assumptions as Facts

### Pattern

A team assumes:

> "Users will definitely prefer this feature."

without evidence.

### AgileFlow Response

Separate:

```text
Known fact
    ↓
Assumption
    ↓
Hypothesis
    ↓
Evidence needed
```

Do not present assumptions as established facts.

---

# 60. Antipattern: Confusing Correlation With Cause

### Pattern

Example:

> "Our velocity decreased after we changed the UI, so the UI change caused the problem."

### AgileFlow Response

This is an interpretation rather than an established causal relationship.

Inspect other relevant factors before identifying a cause.

Possible factors may include:

* work size
* team changes
* interruptions
* dependencies
* estimation changes
* technical complexity

---

# 61. Troubleshooting Workflow

When AgileFlow detects a possible Agile/Scrum antipattern, use:

### Step 1 — Identify the observed behavior

State what is actually known.

### Step 2 — Identify the relevant Scrum or Agile concept

Determine what framework element or principle is involved.

### Step 3 — Classify the practice

Use:

* [SCRUM]
* [AGILE]
* [PRACTICE]
* [OPTIONAL]
* [TEAM]
* [COURSE]
* [UNKNOWN]

### Step 4 — Explain the distinction

Do not simply say:

> "Wrong."

Explain why the concepts differ.

### Step 5 — Identify possible consequences

Only when supported by the situation.

### Step 6 — Suggest possible adaptations

Do not impose unnecessary process.

### Step 7 — Identify what to inspect next

Help the user gather evidence.

---

# 62. Response Pattern for Misconceptions

AgileFlow should generally use:

```text
Claim
  ↓
What Scrum/Agile actually says
  ↓
Classification
  ↓
Why the distinction matters
  ↓
Context-specific guidance
```

Example:

> "Scrum requires story points."

AgileFlow response:

```text
Story points are a commonly used relative estimation practice,
but they are not required by Scrum.

Classification:
Story points → [OPTIONAL] / [PRACTICE]

If your team uses them, define the scale within your own team
and avoid treating points as hours or individual performance.
```

---

# 63. When the User's Practice Is Valid

AgileFlow should not label a team practice as wrong merely because Scrum does not require it.

Example:

> "Our team uses Planning Poker."

Appropriate response:

> Planning Poker is an optional estimation technique. It can be used alongside Scrum, provided the team finds it useful.

Classification: [OPTIONAL]

The absence of a practice from Scrum does not automatically make the practice invalid.

---

# 64. When a Course Requires a Practice

Academic environments may require specific formats or techniques.

For example, a course may require:

* user stories
* acceptance criteria
* story points
* backlog templates
* UML diagrams
* Sprint documentation

AgileFlow should classify these as:

[COURSE]

when they are requirements of the academic context.

It should not incorrectly claim that they are mandatory Scrum requirements.

---

# 65. Academic Example

If a student asks:

> "My teacher requires 20 user stories. Does Scrum require 20 user stories?"

AgileFlow should answer:

```text
Your course requirement:
20 user stories → [COURSE]

Scrum requirement:
User stories → not mandatory
```

The student can satisfy the course requirement without incorrectly describing it as a Scrum requirement.

---

# 66. Classification Reference

| Concept / Practice          | Classification          |
| --------------------------- | ----------------------- |
| Agile Manifesto values      | [AGILE]                 |
| Agile principles            | [AGILE]                 |
| Scrum framework             | [SCRUM]                 |
| Product Backlog             | [SCRUM]                 |
| Product Goal                | [SCRUM]                 |
| Sprint                      | [SCRUM]                 |
| Sprint Goal                 | [SCRUM]                 |
| Sprint Backlog              | [SCRUM]                 |
| Daily Scrum                 | [SCRUM]                 |
| Sprint Review               | [SCRUM]                 |
| Sprint Retrospective        | [SCRUM]                 |
| Increment                   | [SCRUM]                 |
| Definition of Done          | [SCRUM]                 |
| User stories                | [PRACTICE]              |
| Acceptance criteria         | [PRACTICE]              |
| Definition of Ready         | [PRACTICE]              |
| Story points                | [OPTIONAL] / [PRACTICE] |
| Planning Poker              | [OPTIONAL]              |
| Fibonacci estimation        | [OPTIONAL] / [TEAM]     |
| Velocity                    | [OPTIONAL]              |
| Burndown charts             | [OPTIONAL]              |
| Jira                        | [TEAM] / [PRACTICE]     |
| Two-week Sprint             | [TEAM] / [PRACTICE]     |
| Three Daily Scrum questions | [PRACTICE]              |
| Unit testing                | [PRACTICE] / [TEAM]     |
| Code review                 | [PRACTICE] / [TEAM]     |
| TDD                         | [OPTIONAL] / [PRACTICE] |
| Continuous Integration      | [PRACTICE] / [OPTIONAL] |
| Specific backlog template   | [TEAM] / [PRACTICE]     |
| Course-required artifact    | [COURSE]                |
| Missing information         | [UNKNOWN]               |

---

# 67. Agent Decision Rules

When a user presents an Agile/Scrum claim, AgileFlow should:

1. Identify the claim.
2. Identify the relevant concept.
3. Determine whether it is formal Scrum, Agile guidance, a practice, optional technique, team convention, course requirement, or unknown.
4. Explain the distinction.
5. Avoid unnecessary correction when the practice itself is valid.
6. Never turn common practices into mandatory Scrum rules.
7. Never invent missing information.
8. Label assumptions.
9. Separate facts from interpretations.
10. Separate correlation from causation.
11. Use evidence when troubleshooting.
12. Avoid blaming individuals without evidence.
13. Avoid imposing unnecessary ceremonies or tools.
14. Preserve the user's context.
15. Ask clarifying questions when the classification depends on missing information.

---

# 68. Core Antipattern Rule

> The presence of a common Agile practice does not make that practice a Scrum requirement.

AgileFlow should continuously distinguish:

```text
What Scrum defines
        ↓
What Agile principles support
        ↓
What teams commonly practice
        ↓
What is optional
        ↓
What a course requires
        ↓
What a particular team chooses
        ↓
What is unknown
```

The purpose of correcting misconceptions is to improve understanding and decision-making, not to force every team into one Agile workflow.


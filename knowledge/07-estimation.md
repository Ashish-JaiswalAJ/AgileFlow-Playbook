# Estimation & Sizing

## 1. Purpose

This document explains estimation and sizing in Agile/Scrum contexts.

It covers:

- Product Backlog Item sizing
- relative estimation
- story points
- Planning Poker
- team-based estimation
- uncertainty
- estimation vs commitment
- estimation vs ordering
- velocity
- common estimation misconceptions

The central rule is:

> Estimation is a way to support planning and understanding. It is not a guarantee of delivery and should not be treated as an individual performance measurement.

---

# 2. Estimation in Agile

Agile teams may estimate work to help understand:

- relative size
- complexity
- uncertainty
- effort
- dependencies
- planning considerations

However, Agile does not prescribe one universal estimation method.

Classification: [AGILE] / [PRACTICE]

AgileFlow should therefore ask about the team's existing estimation approach before imposing a particular technique.

---

# 3. Product Backlog Item Sizing

Product Backlog Items are ordered and may be sized.

Sizing helps the team understand the relative amount of work associated with PBIs.

Classification: [SCRUM]

The Playbook distinguishes between:

- ordering
- sizing
- estimation
- commitment

These concepts should not be treated as interchangeable.

---

# 4. Relative Estimation

Relative estimation compares one item with another rather than attempting to predict an exact number of hours or days.

Example:

```text
Item A → small
Item B → approximately twice the size of A
Item C → significantly larger than B
````

The purpose is comparison rather than false precision.

Classification: [PRACTICE]

---

# 5. Story Points

Story points are a commonly used relative estimation technique.

They may represent a team's perception of factors such as:

* relative size
* complexity
* effort
* uncertainty

Classification: [PRACTICE]

### Important boundary

Story points are not a formal Scrum requirement.

A Scrum Team can use Scrum without story points.

Classification: [OPTIONAL] / [PRACTICE]

AgileFlow should never say:

> "Every Scrum Team must use story points."

---

# 6. Story Points Are Team-Specific

Story points do not have a universal meaning across teams.

For example:

```text
Team A:
5 points = their reference size

Team B:
5 points = a different reference size
```

The number only has meaning within the team's own estimation system.

Therefore, comparing story-point totals between different teams is generally inappropriate.

Classification: [PRACTICE]

---

# 7. Planning Poker

Planning Poker is a collaborative estimation technique.

Team members independently select an estimate and then discuss differences.

Classification: [OPTIONAL]

Planning Poker is not required by Scrum.

AgileFlow should present it as one possible technique rather than the official Scrum estimation method.

---

# 8. Why Independent Estimates Can Be Useful

When team members estimate independently before discussion, large differences can reveal different understandings of the work.

For example:

```text
Developer A → 3
Developer B → 5
Developer C → 13
```

The difference may indicate uncertainty or different assumptions.

The discussion can then clarify:

* requirements
* complexity
* dependencies
* technical uncertainty
* hidden work

Classification: [PRACTICE]

---

# 9. Estimation Should Support Understanding

The purpose of estimation should not simply be:

> "Get the correct number."

Instead, estimation can help expose differences in understanding.

If estimates differ significantly, AgileFlow should encourage the team to investigate why.

Possible reasons include:

* different assumptions
* unclear requirements
* unknown technical complexity
* dependencies
* different interpretations of scope

These are possibilities, not automatically established causes.

---

# 10. Estimation and Uncertainty

A larger estimate may reflect more than effort.

It may reflect uncertainty or complexity.

For example:

```text
Small known task
    ↓
Lower uncertainty

Large unfamiliar task
    ↓
Higher uncertainty
```

AgileFlow should avoid interpreting an estimate as a precise measurement of time.

Classification: [PRACTICE]

---

# 11. Estimate vs Exact Duration

An estimate is not automatically a promise that work will take exactly that amount of time.

For example:

> "This PBI is estimated at 8 story points."

does not mean:

> "This PBI will take exactly 8 hours."

Story points are relative and team-specific.

Classification: [PRACTICE]

---

# 12. Estimation vs Commitment

Estimation and commitment should be kept conceptually separate.

An estimate communicates the team's current understanding of the relative size or uncertainty of work.

A commitment concerns what the team intends to accomplish in a particular context.

Do not automatically convert:

```text
Estimate
   ↓
Guaranteed delivery
```

Classification: [PRACTICE]

---

# 13. Estimates Can Change

Estimates are based on what the team knows at the time.

As the team learns more, its understanding may change.

Therefore:

```text
Initial understanding
       ↓
Estimate
       ↓
New information
       ↓
Updated understanding
```

AgileFlow should not treat changed estimates as automatically meaning that the team estimated incorrectly.

The reason for the change should be investigated.

---

# 14. Splitting Large PBIs Before Estimation

If a PBI is too large or poorly understood, the team may benefit from refining or splitting it before estimating.

Possible approaches include:

* separating meaningful capabilities
* separating independent outcomes
* identifying different user flows
* isolating complex areas
* reducing unnecessary scope

Classification: [PRACTICE]

AgileFlow should not prescribe one universal splitting technique.

---

# 15. Estimation and Refinement

Product Backlog refinement can improve understanding before work is selected for a Sprint.

During refinement, a team may:

* clarify requirements
* identify ambiguity
* split large PBIs
* identify dependencies
* improve descriptions
* estimate or resize work

Classification: [PRACTICE]

Refinement is an ongoing activity rather than a mandatory separate Scrum event.

---

# 16. Estimation and Ordering Are Different

Ordering answers:

> "Which work is more important or should come first?"

Estimation/sizing answers:

> "How large or complex does this work appear relative to other work?"

A high-priority item is not automatically a small item.

A large item is not automatically low priority.

Classification:

* Product Backlog ordering: [SCRUM]
* Estimation/sizing technique: [PRACTICE]

---

# 17. Estimation and Priority Are Different

Do not use estimated size as a substitute for product value or priority.

Example:

```text
PBI A → high value, large size
PBI B → lower value, small size
```

The team should not automatically conclude that B must be done first simply because it is smaller.

The Product Owner is accountable for Product Backlog ordering.

Classification:

* Product Backlog ordering: [SCRUM]
* Relative sizing: [PRACTICE]

---

# 18. Velocity

Velocity is a commonly used Agile metric based on the amount of estimated work completed by a team over time.

Classification: [OPTIONAL]

Velocity may provide historical information that can support planning.

However, velocity:

* is not required by Scrum
* is not a Scrum artifact
* is not a universal productivity measure
* should not be treated as a guaranteed future capacity

---

# 19. Velocity Is Historical Information

A team's previous velocity can provide information about what has happened historically.

It should not automatically be treated as:

> "The team will definitely complete exactly this many points next Sprint."

Example:

```text
Previous Sprints:
24
28
25
31
```

These values describe historical observations.

They do not create a guaranteed future result.

Classification: [OPTIONAL]

---

# 20. Do Not Use Velocity as an Individual Performance Metric

Story points and velocity should not be used to rank individual Developers.

For example:

```text
Developer A → 20 points
Developer B → 12 points
```

This does not establish that Developer A is more productive.

Story points are team-specific and relative.

Work may differ substantially in:

* complexity
* uncertainty
* collaboration requirements
* type of work
* technical difficulty

Classification: [OPTIONAL] / [PRACTICE]

---

# 21. Velocity Manipulation

A team should not be encouraged to artificially increase story-point estimates simply to produce a higher velocity number.

For example:

```text
Before:
PBI = 5 points

After artificially changing scale:
PBI = 13 points
```

The resulting velocity number would not represent a genuine increase in delivered work.

AgileFlow should identify this as a measurement problem rather than treating the larger number as improved performance.

Classification: [PRACTICE]

---

# 22. Velocity and Team Changes

Velocity is specific to the team's estimation system and context.

Changes in:

* team composition
* estimation scale
* work type
* product context
* workflow

can affect velocity.

Therefore, AgileFlow should avoid directly comparing historical velocity values when the underlying context has materially changed.

Classification: [OPTIONAL]

---

# 23. Estimation Techniques

Possible estimation techniques include:

* relative sizing
* story points
* Planning Poker
* other team-defined sizing approaches

The team may select a technique appropriate to its context.

Classification: [OPTIONAL] / [PRACTICE]

AgileFlow should not present one technique as universally required.

---

# 24. When Estimation May Be Difficult

Estimation may be difficult when:

* requirements are unclear
* the work is unfamiliar
* dependencies are unknown
* technical uncertainty is high
* the PBI is too large
* assumptions differ between team members

AgileFlow should respond by helping clarify the uncertainty rather than pretending that a precise estimate can be produced.

---

# 25. Handling Unknowns

When important information is unavailable, AgileFlow should explicitly identify the uncertainty.

Example:

> "The team cannot reliably size this PBI because the external dependency has not been clarified."

Do not invent:

* exact effort
* exact duration
* missing requirements
* dependency behavior
* team capacity

Instead, identify what information is needed.

Classification: [UNKNOWN] when the information is not established.

---

# 26. Estimation Workflow

When a user asks AgileFlow to estimate a PBI:

### Step 1 — Understand the PBI

Identify:

* intended outcome
* scope
* actors or users where relevant
* known constraints

### Step 2 — Identify ambiguity

Look for:

* unclear requirements
* missing business rules
* unknown dependencies
* technical uncertainty

### Step 3 — Check size

Determine whether the PBI is sufficiently understood and appropriately sized for estimation.

### Step 4 — Identify the team's method

Ask whether the team uses:

* story points
* relative sizing
* Planning Poker
* another method

Do not assume a method if none has been provided.

### Step 5 — Estimate

Use the team's selected approach.

### Step 6 — Explain uncertainty

Clearly distinguish:

* estimate
* assumptions
* unknowns

### Step 7 — Validate

Ask whether the estimate reflects the team's shared understanding.

---

# 27. Example: Story Point Estimation

User requirement:

> As a customer, I want to join a queue online so that I can receive a token without waiting physically.

Suppose the team uses story points.

The team may compare the PBI with reference items:

```text
Reference A → 2 points
Reference B → 5 points
Reference C → 8 points
```

The team discusses the new PBI and selects a relative size based on its understanding.

AgileFlow should not declare a universally correct point value without the team's context.

---

# 28. Example: Large Estimate

Suppose a team estimates a PBI as very large.

AgileFlow should consider asking:

* Is the PBI too broad?
* Are multiple capabilities included?
* Are requirements unclear?
* Is there significant technical uncertainty?
* Are dependencies involved?

The appropriate response may be refinement or splitting rather than simply assigning a larger number.

Classification: [PRACTICE]

---

# 29. Estimate Review

When reviewing an existing estimate, AgileFlow should ask:

1. What estimation method is being used?
2. Is the team's reference scale clear?
3. Is the PBI sufficiently understood?
4. Is the PBI appropriately sized?
5. Are assumptions explicit?
6. Are dependencies known?
7. Is uncertainty visible?
8. Is the estimate being incorrectly treated as a guarantee?

---

# 30. Common Estimation Misconceptions

### Misconception 1

> "Scrum requires story points."

Correction:

Story points are not a formal Scrum requirement.

Classification: [OPTIONAL] / [PRACTICE]

---

### Misconception 2

> "Planning Poker is part of Scrum."

Correction:

Planning Poker is an optional estimation technique.

Classification: [OPTIONAL]

---

### Misconception 3

> "8 story points means 8 hours."

Correction:

Story points are commonly used as relative measures and do not inherently represent hours.

Classification: [PRACTICE]

---

### Misconception 4

> "The estimate is a guarantee."

Correction:

An estimate represents current understanding and should not automatically be treated as a guaranteed delivery commitment.

---

### Misconception 5

> "Higher velocity means better Developers."

Correction:

Velocity is a team-level historical metric when used and should not be used as an individual performance ranking.

---

### Misconception 6

> "Velocity must increase every Sprint."

Correction:

Velocity is optional and is not a Scrum requirement or universal performance target.

---

### Misconception 7

> "A large estimate means the team is inefficient."

Correction:

A large estimate can reflect size, complexity, uncertainty, or other factors.

Investigate the reason before drawing conclusions.

---

### Misconception 8

> "Every PBI needs an exact estimate."

Correction:

AgileFlow should not invent precision when the available information does not support it.

---

# 31. Classification Reference

| Concept                                   | Classification          |
| ----------------------------------------- | ----------------------- |
| Product Backlog Item sizing               | [SCRUM]                 |
| Relative estimation                       | [PRACTICE]              |
| Story points                              | [OPTIONAL] / [PRACTICE] |
| Planning Poker                            | [OPTIONAL]              |
| Estimation discussion                     | [PRACTICE]              |
| PBI splitting before estimation           | [PRACTICE]              |
| Refinement                                | [PRACTICE]              |
| Product Backlog ordering                  | [SCRUM]                 |
| Velocity                                  | [OPTIONAL]              |
| Velocity as individual performance metric | Not appropriate         |
| Specific estimation scale                 | [TEAM] / [PRACTICE]     |
| Exact duration prediction                 | Not guaranteed          |
| Estimation method                         | [TEAM] / [PRACTICE]     |

---

# 32. Agent Decision Rules

When handling estimation questions, AgileFlow should:

1. Identify whether the user is asking about Scrum rules or an Agile practice.
2. Ask for the team's estimation method when it matters.
3. Never assume story points are mandatory.
4. Never assume Planning Poker is mandatory.
5. Never treat estimates as guarantees.
6. Never invent missing information.
7. Separate size from priority.
8. Separate estimates from commitments.
9. Treat velocity as optional.
10. Never use velocity to rank individual Developers.
11. Identify uncertainty explicitly.
12. Suggest refinement or splitting when a PBI is too large or unclear.
13. Preserve the team's established estimation convention when provided.
14. Explain that estimates may change as understanding improves.

---

# 33. Core Estimation Rule

> Estimation supports shared understanding and planning; it is not a promise, universal Scrum requirement, or individual performance score.

AgileFlow should help teams understand:

```text
Requirement
    ↓
Clarification
    ↓
Sizing / Estimation
    ↓
Shared understanding
    ↓
Planning
    ↓
Inspection
    ↓
Adaptation
```

The specific estimation technique should remain appropriate to the team's context rather than being imposed as a universal Agile or Scrum rule.


**Next → `08-quality-and-definition-of-done.md`**.

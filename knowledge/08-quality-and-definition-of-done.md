# Quality & Definition of Done

## 1. Purpose

This document explains quality in Agile/Scrum and the role of the Definition of Done.

It covers:

- product quality
- Definition of Done
- Increment
- quality criteria
- testing
- technical practices
- acceptance criteria vs Definition of Done
- incomplete work
- quality during the Sprint
- common misconceptions

The central rule is:

> Quality is not something that is added only at the end of a Sprint. Work included in the Increment must meet the Definition of Done.

---

# 2. Quality in Agile

Agile emphasizes delivering working and valuable product outcomes while continuously inspecting and adapting.

Quality should therefore be considered throughout development rather than treated only as a final activity.

Classification: [AGILE] / [SCRUM]

AgileFlow should help users distinguish:

- product-specific acceptance conditions
- the team's Definition of Done
- engineering/testing practices
- Scrum requirements

---

# 3. Definition of Done

The Definition of Done is a formal description of the state of the Increment when it meets the quality measures required for the product.

It creates a shared understanding of what it means for work to be complete.

Classification: [SCRUM]

The Definition of Done is a commitment associated with the Increment.

---

# 4. Purpose of the Definition of Done

The Definition of Done creates transparency about the quality state of the Increment.

It helps the Scrum Team understand:

> "What does Done mean for this product?"

A common understanding of Done helps prevent different team members from using different meanings of completion.

Classification: [SCRUM]

---

# 5. Definition of Done and Increment

An Increment must meet the Definition of Done.

If a Product Backlog Item does not meet the Definition of Done, it is not part of the Increment.

Core relationship:

```text
Work
  ↓
Meets Definition of Done
  ↓
Usable Increment
````

Classification: [SCRUM]

---

# 6. Definition of Done Is Not the Same as "Task Completed"

A task being marked complete does not automatically mean that the associated product work is Done.

For example:

```text
Coding completed
      ↓
Testing completed?
      ↓
Required quality checks completed?
      ↓
Definition of Done satisfied?
      ↓
Done
```

The exact checks depend on the team's Definition of Done.

AgileFlow should not invent a universal checklist.

---

# 7. Definition of Done Is Product-Specific

The Definition of Done depends on the product and the organization's context.

A team may define quality expectations appropriate to its product.

Possible examples may include:

* required testing
* integration checks
* documentation
* security checks
* code review
* deployment readiness

These are examples of possible criteria, not universal Scrum requirements.

Classification: [TEAM] / [PRACTICE]

---

# 8. Scrum Requirement vs Engineering Practice

Scrum defines the importance of the Definition of Done, but it does not prescribe one engineering checklist.

For example:

* Definition of Done: [SCRUM]
* automated testing: [PRACTICE]
* code review: [PRACTICE]
* Continuous Integration: [PRACTICE]
* Test-Driven Development: [OPTIONAL] / [PRACTICE]
* specific testing framework: [TEAM]

AgileFlow must preserve this distinction.

---

# 9. Definition of Done and Quality

The Definition of Done should make quality expectations transparent.

A weak Definition of Done may create ambiguity such as:

> "Feature completed."

A clearer team-defined expectation could specify the quality state required before work is considered Done.

The exact content must come from the product/team context.

AgileFlow should not silently add quality requirements.

---

# 10. Definition of Done and Acceptance Criteria

Acceptance criteria and the Definition of Done serve different purposes.

### Acceptance Criteria

Acceptance criteria describe conditions associated with a particular Product Backlog Item.

Classification: [PRACTICE]

### Definition of Done

The Definition of Done describes the quality state required for an Increment.

Classification: [SCRUM]

A PBI may satisfy its acceptance criteria but still fail to meet the Definition of Done.

---

# 11. Example: Acceptance Criteria vs Definition of Done

Suppose a PBI describes an online registration feature.

Acceptance criteria might describe product behavior such as:

```text
Given a valid registration form
When the user submits it
Then an account is created.
```

The Definition of Done may separately require the team's established quality conditions.

For example, if the team has defined:

```text
- required tests completed
- required review completed
- required quality checks completed
```

then satisfying only the acceptance criteria does not automatically make the PBI Done.

Classification:

* Acceptance criteria: [PRACTICE]
* Definition of Done: [SCRUM]
* Specific quality checklist: [TEAM] / [PRACTICE]

---

# 12. Definition of Done vs Definition of Ready

These concepts must not be confused.

### Definition of Done

Describes the quality state required for completed work to be part of the Increment.

Classification: [SCRUM]

### Definition of Ready

A commonly used team practice describing conditions a PBI may satisfy before a team considers it ready for selection or development.

Classification: [PRACTICE]

Scrum does not require a Definition of Ready.

AgileFlow should never present Definition of Ready as a mandatory Scrum artifact or requirement.

---

# 13. Definition of Done vs Acceptance Criteria vs Tasks

These three concepts operate at different levels.

```text
Product Backlog Item
        ↓
Acceptance Criteria
        ↓
Implementation / Tasks
        ↓
Definition of Done
        ↓
Increment
```

### Product Backlog Item

Describes work or a product opportunity.

### Acceptance Criteria

Describes conditions for the specific item.

### Tasks

Describe implementation work when the team chooses to use them.

### Definition of Done

Describes the quality state required for the Increment.

---

# 14. Testing and Quality

Testing can be part of a team's approach to achieving quality.

The specific testing strategy depends on the product and team context.

Possible testing practices include:

* unit testing
* integration testing
* system testing
* acceptance testing
* regression testing
* automated testing
* manual testing

These should not automatically be treated as mandatory Scrum requirements.

Classification: [PRACTICE] / [TEAM]

AgileFlow should ask about the team's existing quality approach when relevant.

---

# 15. Technical Practices

Teams may use engineering practices to maintain quality.

Possible practices include:

* code review
* automated tests
* Continuous Integration
* refactoring
* Test-Driven Development
* static analysis
* automated deployment checks

These are complementary practices.

Scrum does not prescribe a particular technical implementation process.

Classification: [PRACTICE] / [OPTIONAL]

---

# 16. Do Not Invent a Definition of Done

When a user asks:

> "Create a Definition of Done for my project."

AgileFlow may provide a proposed example, but must clearly identify it as a proposed team convention rather than an official Scrum checklist.

Before finalizing it, AgileFlow should ask about relevant context when necessary, such as:

* product type
* quality expectations
* testing expectations
* deployment environment
* security requirements
* documentation needs
* team practices

If information is missing, assumptions must be clearly labeled.

---

# 17. Example Proposed Definition of Done

A generic example may be structured as:

```text
A Product Backlog Item is Done when:

- the agreed product behavior is implemented
- relevant acceptance conditions are satisfied
- required testing is completed
- identified defects affecting the agreed quality level are addressed
- required reviews/checks are completed
- the work satisfies the team's Definition of Done
```

This is an example only.

Classification: [TEAM] / [PRACTICE]

AgileFlow must not present this exact checklist as the universal Scrum Definition of Done.

---

# 18. Definition of Done Can Evolve

The Definition of Done may be improved as the team learns.

During inspection and adaptation, the team may identify quality gaps and update its quality expectations.

Changes should improve transparency and the quality of future Increments.

Classification: [SCRUM] / [PRACTICE]

AgileFlow should distinguish between:

* the existence of a Definition of Done: [SCRUM]
* the team's specific contents: [TEAM]

---

# 19. Organizational Definition of Done

If an organization has an established Definition of Done, Scrum Teams should follow the applicable organizational standard.

The Scrum Team may also create a more stringent Definition of Done when appropriate to the product.

AgileFlow should ask about organizational constraints before proposing a team-specific Definition of Done.

Classification: [SCRUM]

---

# 20. Definition of Done and Multiple Teams

When multiple Scrum Teams work together on the same product, a shared Definition of Done helps establish a common quality standard for the Increment.

AgileFlow should not assume that each team can independently define incompatible quality meanings when they are contributing to the same product.

Classification: [SCRUM]

---

# 21. Incomplete Work

If work does not satisfy the Definition of Done:

* it is not part of the Increment
* it should not be represented as Done
* the team should maintain transparency about its state

AgileFlow should avoid encouraging teams to hide incomplete work simply to meet Sprint targets.

Classification: [SCRUM]

---

# 22. Quality Should Not Be Reduced to Meet the Sprint Goal

A team should not lower its Definition of Done simply to make more work appear completed.

For example:

```text
Original quality requirement
        ↓
Sprint pressure
        ↓
Remove testing
        ↓
Mark feature Done
```

This creates a misleading quality state.

The Definition of Done represents the quality standard required for an Increment.

Classification: [SCRUM]

---

# 23. Quality and Sprint Scope

When a Sprint is at risk, AgileFlow should distinguish between:

* changing scope
* reducing quality

Scope can be adapted while pursuing the Sprint Goal.

Quality should not be reduced by bypassing the Definition of Done.

Example:

```text
Possible adaptation:
Remove lower-priority scope
        ↓
Protect Sprint Goal
        ↓
Maintain Definition of Done
```

This is different from:

```text
Keep all scope
        ↓
Skip quality requirements
        ↓
Call work Done
```

---

# 24. Acceptance Criteria Can Change

Acceptance criteria may be clarified as requirements become better understood.

AgileFlow should distinguish between:

* changes to a specific PBI's acceptance conditions
* changes to the team's Definition of Done

They are not the same thing.

Classification:

* Acceptance criteria: [PRACTICE]
* Definition of Done: [SCRUM]

---

# 25. Quality Validation Workflow

When reviewing whether a PBI is Done, AgileFlow can use:

### Step 1 — Understand the PBI

Identify what product outcome is expected.

### Step 2 — Check acceptance conditions

Determine whether the specific PBI's acceptance criteria or agreed conditions are satisfied.

### Step 3 — Check Definition of Done

Determine whether the work satisfies the team's Definition of Done.

### Step 4 — Check transparency

Identify anything incomplete or uncertain.

### Step 5 — Determine Increment status

If the work satisfies the Definition of Done, it can be part of the Increment.

---

# 26. Quality Troubleshooting

When a user reports quality problems, AgileFlow should not immediately blame a particular process or person.

Use:

```text
Observed quality problem
        ↓
Evidence
        ↓
Possible causes
        ↓
Current quality practices
        ↓
Potential adaptation
```

Possible causes may include:

* unclear requirements
* insufficient testing
* incomplete refinement
* technical complexity
* missing quality checks
* unclear Definition of Done
* process problems
* environmental constraints

These are possible explanations, not established facts.

AgileFlow should ask for evidence when necessary.

---

# 27. Example: "Everything Is Coded but Nothing Is Done"

If a user says:

> "All coding is complete, so can we mark the feature Done?"

AgileFlow should ask whether the work satisfies the team's Definition of Done.

Coding completion alone does not establish Done.

The relevant question is:

> "Does the work meet the Definition of Done and therefore qualify as part of the Increment?"

---

# 28. Example: "Testing Is Not Finished"

If required testing is part of the team's Definition of Done and testing is incomplete, the work does not meet the Definition of Done.

AgileFlow should not advise the team to mark it Done merely because the Sprint is ending.

Instead, it should help inspect:

* remaining testing
* scope
* Sprint Goal
* quality requirements
* possible adaptation

---

# 29. Quality and Continuous Improvement

Quality improvement can be part of the team's ongoing inspection and adaptation.

The Sprint Retrospective provides an opportunity to identify improvements related to:

* processes
* tools
* interactions
* Definition of Done
* quality practices

AgileFlow should help turn identified problems into observable improvement opportunities.

Classification: [SCRUM]

---

# 30. Common Quality Misconceptions

### Misconception 1

> "Definition of Done is optional."

Correction:

The Definition of Done is part of Scrum's framework and is a commitment associated with the Increment.

Classification: [SCRUM]

---

### Misconception 2

> "Definition of Ready is the same as Definition of Done."

Correction:

Definition of Ready is a team practice concerning readiness for work; Definition of Done describes the quality state required for completed work to be part of the Increment.

Classification:

* Definition of Done: [SCRUM]
* Definition of Ready: [PRACTICE]

---

### Misconception 3

> "Acceptance criteria are the Definition of Done."

Correction:

Acceptance criteria relate to a particular PBI. Definition of Done applies to the quality state of the Increment.

---

### Misconception 4

> "If the code works, it is Done."

Correction:

Working code alone does not establish Done unless the work satisfies the team's Definition of Done.

---

### Misconception 5

> "Testing can always be postponed until after the Sprint."

Correction:

If required quality conditions are not met, the work does not meet the Definition of Done and is not part of the Increment.

---

### Misconception 6

> "Scrum requires unit testing."

Correction:

Scrum does not prescribe a specific testing technique.

A team may establish unit testing as part of its quality practices or Definition of Done.

Classification: [TEAM] / [PRACTICE]

---

### Misconception 7

> "Scrum requires code review."

Correction:

Code review is not a universal Scrum requirement.

A team or organization may include it in its Definition of Done.

Classification: [TEAM] / [PRACTICE]

---

### Misconception 8

> "The Definition of Done should be changed whenever the Sprint is under pressure."

Correction:

The Definition of Done represents the quality standard for the Increment. It should not be weakened merely to make unfinished work appear Done.

---

# 31. Classification Reference

| Concept                                | Classification          |
| -------------------------------------- | ----------------------- |
| Definition of Done                     | [SCRUM]                 |
| Increment must meet Definition of Done | [SCRUM]                 |
| Acceptance criteria                    | [PRACTICE]              |
| Definition of Ready                    | [PRACTICE]              |
| Testing                                | [PRACTICE] / [TEAM]     |
| Unit testing                           | [PRACTICE] / [TEAM]     |
| Code review                            | [PRACTICE] / [TEAM]     |
| Continuous Integration                 | [PRACTICE] / [OPTIONAL] |
| Test-Driven Development                | [OPTIONAL] / [PRACTICE] |
| Specific testing framework             | [TEAM]                  |
| Specific Definition of Done checklist  | [TEAM]                  |
| Quality improvement                    | [SCRUM] / [PRACTICE]    |

---

# 32. Agent Decision Rules

When handling quality questions, AgileFlow should:

1. Identify the team's Definition of Done when available.
2. Distinguish Definition of Done from acceptance criteria.
3. Distinguish Definition of Done from Definition of Ready.
4. Never invent a team's quality requirements without labeling them as proposed.
5. Never present a specific testing method as universally required by Scrum.
6. Never treat coding completion alone as proof of Done.
7. Never encourage lowering quality merely to meet Sprint scope.
8. Identify incomplete work transparently.
9. Ask for relevant team or organizational quality standards when necessary.
10. Distinguish Scrum requirements from engineering practices.
11. Use evidence when troubleshooting quality problems.
12. Clearly label assumptions and unknowns.

---

# 33. Core Quality Rule

> Done means meeting the Definition of Done. Work that does not meet the Definition of Done is not part of the Increment.

AgileFlow should preserve this distinction:

```text
PBI
 ↓
Acceptance Criteria
 ↓
Implementation
 ↓
Definition of Done
 ↓
Increment
```

Acceptance criteria help describe whether a particular PBI satisfies its agreed product conditions.

The Definition of Done establishes the quality state required for work to be part of the Increment.

The specific engineering practices used to achieve that quality should remain appropriate to the team's context rather than being presented as universal Scrum requirements.

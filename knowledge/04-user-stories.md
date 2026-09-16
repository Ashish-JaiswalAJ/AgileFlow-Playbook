# User Stories & Requirement Writing

## 1. Purpose

This document defines how AgileFlow should create, evaluate, refine, split, and explain user stories while maintaining a clear distinction between user-story practices and formal Scrum requirements.

The central rule is:

> User stories are a commonly used Agile practice. Scrum defines Product Backlog Items but does not require the user-story format.

Classification: [PRACTICE]

---

# 2. User Story

A user story is a commonly used Agile technique for expressing a requirement from the perspective of a user or other stakeholder.

A common format is:

> As a [type of user],  
> I want [capability],  
> so that [benefit/value].

A user story should communicate:

- who needs something
- what they need
- why they need it

Classification: [PRACTICE]

---

# 3. Important Scrum Boundary

User stories are **not required by Scrum**.

Scrum defines Product Backlog Items, but does not prescribe a particular user-story format.

Therefore:

> "Use user stories" → [PRACTICE]

Not:

> "Scrum requires user stories." → Incorrect

When a user asks whether user stories are mandatory, explain this distinction directly.

---

# 4. User Story Purpose

A user story helps a team focus on a user need and expected value rather than immediately prescribing a technical implementation.

### Technical statement

> Create a database table for customer tokens.

### User-centered statement

> As a customer, I want to receive a token after registering so that I know my position.

The user-centered version communicates the desired outcome rather than immediately deciding how the system will implement it.

Classification: [PRACTICE]

---

# 5. Core User Story Structure

Use:

> As a [user/actor],  
> I want [capability],  
> so that [benefit/value].

### Actor

Who needs the capability?

Examples:

- customer
- administrator
- staff member
- registered user
- stakeholder

### Capability

What does the actor want to accomplish?

The capability should describe the desired behavior or outcome.

### Benefit / Value

Why does the capability matter?

The value should explain the expected benefit rather than merely repeat the capability.

---

# 6. Agent Workflow for Creating a User Story

When transforming a requirement into a user story, AgileFlow should first identify:

> Actor → Need → Expected benefit

Then construct the story.

AgileFlow should:

1. Preserve the original intent.
2. Identify the actor.
3. Identify the desired capability.
4. Identify the expected value where available.
5. Avoid unnecessary implementation details.
6. Identify missing information.
7. Clearly label assumptions.
8. Avoid inventing business rules.

If the original requirement does not provide enough information to establish the actor or value, AgileFlow should not fabricate them.

Instead, it should either:

- ask for clarification, or
- provide a clearly labeled assumption.

---

# 7. Example

Input:

> Customers should be able to join a service queue online.

Possible user story:

> As a customer,  
> I want to join a service queue online,  
> so that I can register for service without waiting at the location.

The exact benefit should be validated against the user's actual requirement.

AgileFlow must not assume additional behavior such as:

- SMS notifications
- QR codes
- automatic token generation
- estimated waiting time

unless those requirements are actually provided.

Classification: [PRACTICE]

---

# 8. User Story vs Product Backlog Item

These concepts must not be treated as identical.

### Product Backlog Item

A formal Scrum concept representing work in the Product Backlog.

Classification: [SCRUM]

### User Story

A common technique for expressing a requirement or PBI.

Classification: [PRACTICE]

A user story can represent a PBI, but not every PBI must use the user-story format.

---

# 9. User Story vs Technical Task

A user story generally expresses a user or stakeholder need and expected value.

A technical task describes implementation work required to achieve an outcome.

### User story

> As a customer, I want to receive a token after registration so that I know my queue position.

### Technical task

> Implement token generation logic.

The technical task may contribute to the user story, but it does not communicate the same user-facing outcome.

Classification: [PRACTICE]

### Agent Guidance

When a user provides a technical implementation statement and asks for a user story, AgileFlow should identify the underlying user outcome before rewriting it.

Do not simply place technical language into:

> As a user, I want...

---

# 10. User Story vs Acceptance Criteria

These serve different purposes.

### User Story

Communicates:

- actor
- desired capability
- expected value

### Acceptance Criteria

Define specific conditions that can be used to determine whether the requirement has been satisfied.

Acceptance criteria are a complementary practice.

Classification: [PRACTICE]

Do not replace a user story with acceptance criteria or treat the two as the same artifact.

---

# 11. User Stories and Functional Requirements

A functional requirement describes behavior or capability the system should provide.

A user story is one possible way to express such a requirement.

Example:

### Functional requirement

> The system shall allow users to register for an available queue.

### User story

> As a user, I want to register for an available queue so that I can receive a position in the queue.

AgileFlow may convert between these representations when requested.

The conversion should preserve the original meaning.

---

# 12. User Stories and Non-Functional Requirements

Not every requirement fits naturally into a traditional user-story format.

Examples of non-functional concerns include:

- performance
- security
- reliability
- availability
- accessibility
- maintainability

AgileFlow should not force every technical or quality requirement into an artificial user-story structure.

If a user asks for user stories for non-functional requirements, AgileFlow should preserve the underlying quality concern and explain any limitations of the representation.

Classification: [PRACTICE]

---

# 13. Business Rules

Business rules may be associated with a user story but should not be invented.

Example:

Requirement:

> A customer can cancel a booking until two hours before the appointment.

The two-hour condition is a business rule.

AgileFlow should preserve it when rewriting the requirement.

It should not silently change it to:

> Customers can cancel until one hour before the appointment.

### Rule

Preserve explicit business rules exactly unless the user asks for modification.

Classification: [PRACTICE]

---

# 14. Ambiguous User Stories

AgileFlow should identify ambiguity rather than silently resolving it.

Examples:

> As a user, I want fast service.

Questions:

- What does "fast" mean?
- Which service?
- What measurable outcome is expected?

Another example:

> As an admin, I want to manage users.

Questions:

- What management actions?
- Create?
- Edit?
- Disable?
- Delete?
- View?

AgileFlow should identify these gaps and request clarification when they materially affect the requirement.

Classification: [PRACTICE]

---

# 15. User Story Quality

When reviewing a user story, AgileFlow should examine:

### Actor

Is the intended user or stakeholder clear?

### Need

Is the requested capability understandable?

### Value

Is the reason or expected benefit clear?

### Scope

Is the story too broad?

### Ambiguity

Are important terms unclear?

### Implementation

Does the story unnecessarily prescribe a technical solution?

### Completeness

Is important information missing?

### Testability

Can the expected outcome eventually be evaluated?

These are review considerations, not additional Scrum requirements.

Classification: [PRACTICE]

---

# 16. INVEST

INVEST is a commonly used checklist for evaluating user stories.

The acronym is commonly expanded as:

- Independent
- Negotiable
- Valuable
- Estimable
- Small
- Testable

INVEST can be useful when reviewing user stories.

However:

> INVEST is not a formal Scrum requirement.

Classification: [OPTIONAL] / [PRACTICE]

AgileFlow should not reject a Product Backlog Item simply because it does not satisfy every INVEST criterion.

---

# 17. Splitting Large User Stories

A user story may be too large to work with effectively.

AgileFlow can help split it into smaller stories.

Possible approaches include splitting by:

- user workflow
- business capability
- scenario
- independent outcome
- business rule
- data variation
- user type where appropriate

The objective should be meaningful smaller slices rather than arbitrary technical fragments.

Classification: [PRACTICE]

---

# 18. Example of Story Splitting

Large story:

> As a customer, I want to manage my account so that I can maintain my information.

This may be too broad.

Possible smaller stories could include:

> As a customer, I want to view my account information so that I can verify my details.

> As a customer, I want to update my account information so that my details remain current.

> As a customer, I want to change my password so that I can maintain account security.

These examples are illustrative. AgileFlow should validate the actual requirements before generating final stories.

---

# 19. Avoid Technical Decomposition as User Stories

Do not automatically turn technical tasks into separate user stories.

Example:

Technical tasks:

- create database table
- create API endpoint
- implement frontend form
- write unit tests

These may be implementation tasks associated with a larger Product Backlog Item.

They are not automatically separate user stories.

AgileFlow should distinguish:

> user-facing outcome

from:

> implementation work.

Classification: [PRACTICE]

---

# 20. User Story Assumptions

When information is missing, AgileFlow must distinguish assumptions from confirmed requirements.

Example:

Input:

> As an admin, I want to receive alerts.

Unknown:

- Which alerts?
- Through what channel?
- When should they be sent?
- What events trigger them?

AgileFlow should not automatically assume:

> email notifications

or:

> SMS notifications

unless that information is provided.

Use language such as:

> "The notification channel is not specified."

Classification: [UNKNOWN] when the available sources do not establish the answer.

---

# 21. User Story Validation

When validating a user story, AgileFlow should check:

1. Is the actor identifiable?
2. Is the desired capability clear?
3. Is the value or purpose understandable?
4. Are important business rules preserved?
5. Is the scope understandable?
6. Are important assumptions visible?
7. Is implementation unnecessarily prescribed?
8. Are important ambiguities identified?
9. Can acceptance criteria later be defined?
10. Does the story represent the intended user outcome?

Do not claim that a story is "officially Scrum-compliant" merely because it follows this structure.

User stories are a practice, not a formal Scrum artifact.

---

# 22. User Story Rewriting Workflow

When a user gives AgileFlow a vague requirement and asks for a user story:

### Step 1 — Preserve intent

Identify what the user actually wants.

### Step 2 — Identify actor

Determine who needs the capability.

### Step 3 — Identify capability

Determine what the actor needs to accomplish.

### Step 4 — Identify value

Determine why the capability matters.

### Step 5 — Detect ambiguity

Identify information that cannot safely be inferred.

### Step 6 — Write the story

Use the standard format when appropriate.

### Step 7 — State assumptions

Clearly identify any assumptions made.

### Step 8 — Suggest acceptance criteria

Only when useful or requested.

### Step 9 — Validate

Check that the rewritten story still represents the original requirement.

---

# 23. When Not to Force a User Story

AgileFlow should not automatically convert every piece of information into a user story.

Do not force the format when the user is providing:

- a technical task
- an architectural decision
- a constraint
- a business rule
- a quality requirement
- a course-specific artifact
- a Definition of Done criterion
- an implementation detail

Instead, identify what type of information it represents.

---

# 24. Course and Academic Context

If a user is completing an academic assignment requiring user stories:

Classification: [COURSE]

AgileFlow should help produce the required user stories while maintaining the Scrum distinction.

Example:

> "Your course requires user stories, so we can use the standard user-story format for the assignment. User stories are a common Agile practice, but they are not mandated by Scrum."

Do not reject a course requirement merely because it is not a Scrum requirement.

---

# 25. Common Misconceptions

### Misconception 1

> "User stories are mandatory in Scrum."

Correction:

Scrum requires Product Backlog Items but does not prescribe user stories.

---

### Misconception 2

> "Every Product Backlog Item must follow As a / I want / So that."

Correction:

That is a common user-story format, not a Scrum requirement.

---

### Misconception 3

> "A technical task is automatically a user story."

Correction:

Technical tasks and user stories communicate different types of information.

---

### Misconception 4

> "Every user story must have a completely known solution before refinement."

Correction:

The team can refine understanding over time. AgileFlow should not invent implementation details that have not been established.

---

### Misconception 5

> "INVEST is required by Scrum."

Correction:

INVEST is a commonly used user-story quality checklist, not a formal Scrum requirement.

---

### Misconception 6

> "If a user story is large, split it into frontend and backend stories."

Correction:

Splitting by technical layer is not automatically the best approach. Prefer meaningful outcomes or capabilities where possible.

---

# 26. Classification Reference

| Concept | Classification |
|---|---|
| Product Backlog Item | [SCRUM] |
| User Story | [PRACTICE] |
| As / I want / So that format | [PRACTICE] |
| Acceptance Criteria | [PRACTICE] |
| Acceptance Scenarios | [PRACTICE] |
| INVEST | [OPTIONAL] / [PRACTICE] |
| Functional Requirement | [PRACTICE] |
| Non-functional Requirement | [PRACTICE] |
| Technical Task | [PRACTICE] |
| Business Rule | [PRACTICE] |
| Course-required user-story format | [COURSE] |
| Team-specific story template | [TEAM] |
| Unknown requirement detail | [UNKNOWN] |

---

# 27. Core User Story Rule

> A user story is a useful Agile practice for expressing a user or stakeholder need, but Scrum does not require the user-story format.

When creating or rewriting user stories, AgileFlow must:

- preserve the user's intent
- identify actor, capability, and value
- avoid inventing missing requirements
- identify ambiguity
- distinguish user stories from technical tasks
- distinguish user stories from acceptance criteria
- label assumptions
- treat INVEST as optional
- respect course and team conventions without presenting them as universal Scrum rules

### Final principle

> Use the user-story format when it helps communicate the requirement; do not confuse the format with the Scrum framework itself.

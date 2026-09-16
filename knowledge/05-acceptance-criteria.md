# Acceptance Criteria, Acceptance Scenarios & Validation

## 1. Purpose

This document defines how AgileFlow should understand, create, review, and validate acceptance criteria and acceptance scenarios.

The central rule is:

> Acceptance criteria are a commonly used Agile practice. They help clarify and validate requirements, but they are not a formal Scrum requirement.

Classification: [PRACTICE]

---

# 2. Acceptance Criteria

Acceptance criteria are conditions that describe what a requirement should satisfy to be considered acceptable.

They provide additional detail around a requirement or user story.

They can help the team understand:

- expected behavior
- required outcomes
- important rules
- boundary conditions
- error handling
- scenarios that should be validated

Classification: [PRACTICE]

### Important Scrum Boundary

Scrum does not formally require acceptance criteria.

Therefore:

> "Acceptance criteria are useful for this requirement." → [PRACTICE]

Not:

> "Scrum requires every Product Backlog Item to have acceptance criteria." → Incorrect

AgileFlow must maintain this distinction.

---

# 3. Acceptance Criteria vs Definition of Done

These concepts must not be treated as interchangeable.

## Acceptance Criteria

Acceptance criteria describe conditions specific to a particular requirement or Product Backlog Item.

Classification: [PRACTICE]

## Definition of Done

The Definition of Done is a formal Scrum commitment describing the quality state required for work to be considered Done.

Classification: [SCRUM]

### Example

User story:

> As a customer, I want to reset my password so that I can regain access to my account.

Possible acceptance criteria:

- The user can request a password reset.
- The system validates the reset request.
- The user can set a new valid password.
- An invalid reset attempt is handled appropriately.

Definition of Done may include broader product-quality conditions such as:

- required tests completed
- code integrated
- required quality checks passed
- applicable documentation updated

The exact Definition of Done depends on the product and applicable standards.

Do not create a fake Definition of Done from acceptance criteria.

---

# 4. Purpose of Acceptance Criteria

Acceptance criteria can improve transparency by making expected behavior clearer.

They can help:

- reduce ambiguity
- guide development
- guide testing
- clarify stakeholder expectations
- identify missing scenarios
- support discussions during refinement
- validate whether a requirement has been satisfied

Acceptance criteria should support understanding rather than become unnecessary documentation.

Classification: [PRACTICE]

---

# 5. Characteristics of Useful Acceptance Criteria

When reviewing acceptance criteria, AgileFlow should consider whether they are:

- specific enough to understand
- observable
- testable
- relevant to the requirement
- consistent with stated business rules
- sufficiently clear
- free from unnecessary ambiguity

Avoid criteria that rely on vague terms such as:

- fast
- easy
- user-friendly
- secure
- efficient

unless those terms have been defined or measurable conditions are available.

### Example

Weak:

> The page should load quickly.

More useful:

> The page should display the requested queue status within the agreed performance threshold.

If no threshold has been provided, AgileFlow should not invent one.

Instead:

> "The performance threshold is not specified."

Classification: [UNKNOWN] where the available information does not establish the value.

---

# 6. Given / When / Then

Given / When / Then is a commonly used format for expressing acceptance scenarios.

### Structure

**Given** a known context or initial condition

**When** an action or event occurs

**Then** an expected outcome should occur

Classification: [PRACTICE]

### Example

**Given** a customer has joined an available queue  
**When** the customer submits the registration  
**Then** the system should provide a queue position.

Given / When / Then is useful but is not mandatory Scrum terminology.

AgileFlow must not describe it as a required Scrum format.

---

# 7. Positive Scenarios

Acceptance criteria may describe expected successful behavior.

Example:

User story:

> As a user, I want to log in so that I can access my account.

Scenario:

**Given** the user has valid credentials  
**When** the user submits the login form  
**Then** the system authenticates the user and provides access.

Classification: [PRACTICE]

---

# 8. Negative Scenarios

Where relevant, acceptance criteria should also consider invalid or unsuccessful situations.

Example:

**Given** the user enters an incorrect password  
**When** the user submits the login form  
**Then** the system should not authenticate the user and should provide an appropriate error response.

AgileFlow should consider negative scenarios when they materially affect the requirement.

It should not generate arbitrary error cases simply to increase the number of criteria.

Classification: [PRACTICE]

---

# 9. Edge Cases and Boundaries

Acceptance criteria can identify important boundary conditions.

Examples:

- minimum allowed value
- maximum allowed value
- empty input
- duplicate input
- unavailable resource
- expired session
- invalid format
- missing required information

Example:

Requirement:

> A user can create a password.

Potential questions:

- What is the minimum length?
- Are certain characters required?
- What happens if the password is empty?
- What happens if the password does not meet the required rules?

If these rules are not provided, AgileFlow should identify them as missing information rather than inventing exact requirements.

Classification: [UNKNOWN] when unspecified.

---

# 10. Business Rules in Acceptance Criteria

Explicit business rules should be preserved.

Example:

Requirement:

> A customer may cancel an appointment until two hours before the scheduled time.

Acceptance criteria should preserve the two-hour condition.

AgileFlow must not silently change:

> two hours

to:

> one hour

or any other value.

If the rule appears inconsistent with another source, identify the conflict.

Classification: [PRACTICE]

---

# 11. Acceptance Criteria and Technical Implementation

Acceptance criteria should generally describe expected behavior or outcomes rather than unnecessarily prescribing implementation.

Example:

Less useful as an acceptance criterion:

> The developer must create a PostgreSQL table called `users`.

This is an implementation instruction.

Potential outcome-oriented criterion:

> The system stores the user's required account information and makes it available when the user signs in.

However, if the user explicitly requires PostgreSQL or a particular implementation, preserve that requirement and identify it appropriately.

AgileFlow should not remove explicit technical constraints merely because they are not user-facing.

Classification: [PRACTICE]

---

# 12. Acceptance Criteria vs Technical Tasks

These are different.

### Acceptance Criterion

Describes a condition that the resulting behavior should satisfy.

### Technical Task

Describes work needed to implement the solution.

Example:

Acceptance criterion:

> A registered user receives a unique queue token.

Technical task:

> Implement the token-generation service.

The technical task supports the requirement but does not replace its acceptance condition.

Classification: [PRACTICE]

---

# 13. Completeness Review

When reviewing acceptance criteria, AgileFlow should consider:

### Main success path

Does the normal expected behavior have a criterion?

### Invalid input

Are important invalid inputs addressed?

### Error handling

Are important failure conditions addressed?

### Boundaries

Are relevant minimum/maximum or other boundary conditions defined?

### Business rules

Are explicit rules preserved?

### Permissions

If authorization matters, is the expected behavior clear?

### State changes

If the requirement changes state, is the resulting state understandable?

### External dependencies

If another service or system is involved, are relevant expected outcomes clear?

### Missing information

Are any important conditions unknown?

AgileFlow should not claim that acceptance criteria are complete if important information is still missing.

---

# 14. Validation Questions

When acceptance criteria cannot be written accurately because information is missing, AgileFlow should ask targeted questions.

Examples:

### For a login requirement

- What should happen after successful authentication?
- What should happen after invalid credentials?
- Are account-locking rules specified?
- Is multi-factor authentication required?

### For a payment requirement

- Which payment states must be handled?
- What happens when payment fails?
- What happens when payment is cancelled?
- What happens when the payment provider is unavailable?

### For a queue requirement

- What happens when the queue is full?
- Can a user join multiple queues?
- What happens if the queue closes?
- What happens if the user cancels?

Only ask questions that materially affect the requirement.

---

# 15. Avoid Inventing Requirements

This is a critical AgileFlow rule.

Given:

> "Users can register for an event."

Do not automatically invent:

- email verification
- SMS confirmation
- payment
- cancellation
- waiting list
- QR code
- age restrictions
- identity verification

unless those requirements are supplied or established by an authoritative source relevant to the question.

Instead, say:

> "The requirement establishes event registration, but the available information does not specify confirmation, cancellation, payment, or verification behavior."

Classification: [UNKNOWN]

---

# 16. Multiple Acceptance Scenarios

A single user story may require multiple scenarios.

Example:

User story:

> As a user, I want to reset my password so that I can regain access to my account.

Possible scenarios:

### Successful reset

Given the user has a valid reset request  
When the user submits a valid new password  
Then the password is updated.

### Invalid reset request

Given the reset request is invalid or expired  
When the user attempts to reset the password  
Then the system rejects the request.

### Invalid password

Given the user is resetting the password  
When the new password does not satisfy the defined password rules  
Then the system rejects the new password.

These are examples only. Actual business rules must be confirmed.

---

# 17. Acceptance Criteria Validation Workflow

When validating acceptance criteria, AgileFlow should use:

1. Identify the related user story or PBI.
2. Identify the intended outcome.
3. Compare criteria with the original requirement.
4. Check that explicit business rules are preserved.
5. Check for ambiguity.
6. Check relevant positive scenarios.
7. Check relevant negative scenarios.
8. Check important boundaries.
9. Check whether implementation details are unnecessarily prescribed.
10. Identify missing information.
11. Identify assumptions.
12. Verify that criteria do not contradict one another.
13. Explain any uncertainty.

---

# 18. Requirement → Story → Criteria

A useful workflow is:

```text
Business Need
     ↓
Requirement / Product Backlog Item
     ↓
User Story (if the team uses this practice)
     ↓
Acceptance Criteria / Scenarios (if useful)
     ↓
Implementation
     ↓
Validation
     ↓
Definition of Done
     ↓
Increment

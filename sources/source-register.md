# AgileFlow Source Register

## 1. Purpose

This file records the primary sources used by AgileFlow and explains their intended authority.

AgileFlow should use this register together with the knowledge files to distinguish:

- formal Scrum framework information
- Agile values and principles
- supporting explanations
- academic/course material
- complementary Agile practices
- team-specific conventions

---

# 2. Source Hierarchy

AgileFlow should use the following authority order:

1. Scrum Guide 2020
2. Agile Manifesto and Principles
3. Scrum.org
4. Course/academic material
5. Complementary Agile practices
6. Team-specific conventions

A lower-level source should not silently override a higher-authority source for formal framework definitions.

---

# 3. Primary Scrum Source

## Scrum Guide

**Source:** Scrum Guide 2020

**URL:**
https://scrumguides.org/scrum-guide.html

**Authority:** Primary

**Use for:**

- Scrum definition
- Scrum theory
- empiricism
- Scrum values
- Scrum Team
- Product Owner
- Scrum Master
- Developers
- Sprint
- Sprint Goal
- Sprint Planning
- Sprint Backlog
- Daily Scrum
- Increment
- Definition of Done
- Sprint Review
- Sprint Retrospective
- Product Backlog
- Product Goal
- Product Backlog Items
- Scrum accountabilities
- Scrum events
- Scrum artifacts
- Scrum commitments

**Important rule:**

When AgileFlow needs to determine what Scrum formally requires or defines, this source takes priority.

---

# 4. Agile Manifesto

## Manifesto for Agile Software Development

**Source:** Agile Manifesto

**URL:**
https://agilemanifesto.org/

**Authority:** Primary Agile source

**Use for:**

- Agile values
- Agile philosophy
- distinction between the four value preferences
- understanding the principles behind Agile development

The four values are:

1. Individuals and interactions over processes and tools
2. Working software over comprehensive documentation
3. Customer collaboration over contract negotiation
4. Responding to change over following a plan

The items on the right remain valuable; the items on the left are valued more.

---

# 5. Agile Principles

## Principles Behind the Agile Manifesto

**Source:** Agile Manifesto Principles

**URL:**
https://agilemanifesto.org/principles.html

**Authority:** Primary Agile source

**Use for:**

- Agile principles
- customer value
- responding to change
- frequent delivery
- collaboration
- working software
- sustainable development
- technical excellence
- simplicity
- self-organizing teams
- reflection and adaptation

AgileFlow should use these principles when answering questions about Agile philosophy and values.

---

# 6. Scrum.org

## Scrum.org

**Source:** Scrum.org

**URL:**
https://www.scrum.org/

**Authority:** Supporting

**Use for:**

- practical Scrum explanations
- Scrum terminology
- Scrum learning material
- supporting interpretation and examples

When a formal Scrum definition is required, the Scrum Guide remains the primary authority.

---

# 7. Course and Academic Material

Course or academic material may provide requirements for a particular educational context.

Examples may include:

- user-story requirements
- acceptance-criteria requirements
- backlog templates
- Sprint documentation
- estimation exercises
- UML diagrams
- academic deliverables

Classification:

```text
[COURSE]
````

Course requirements should not automatically be represented as formal Scrum requirements.

Example:

```text
Course requires 20 user stories
        ↓
[COURSE]

User stories are required by Scrum
        ↓
Incorrect classification
```

---

# 8. Complementary Agile Practices

AgileFlow may encounter practices that are widely used with Agile/Scrum but are not formal Scrum requirements.

Examples include:

* user stories
* acceptance criteria
* Definition of Ready
* story points
* Planning Poker
* Fibonacci estimation
* velocity
* burndown charts
* task breakdown
* capacity planning
* code review
* automated testing
* Continuous Integration
* Test-Driven Development
* specific backlog templates

These should be classified as:

```text
[PRACTICE]
```

or:

```text
[OPTIONAL]
```

depending on context.

---

# 9. Team-Specific Conventions

Teams may establish their own ways of working.

Examples include:

* two-week Sprint duration
* specific backlog template
* specific estimation scale
* specific task structure
* particular project-management tool
* specific Definition of Done checklist
* specific testing workflow

Classification:

```text
[TEAM]
```

AgileFlow should respect an explicitly provided team convention without incorrectly describing it as a universal Scrum requirement.

---

# 10. Unknown Information

When the available sources and user context do not establish an answer, AgileFlow should classify the information as:

```text
[UNKNOWN]
```

AgileFlow should not invent:

* missing requirements
* business rules
* team decisions
* technical architecture
* exact estimates
* organizational policies
* unsupported Scrum requirements

When useful, AgileFlow should identify what information is missing and ask for clarification.

---

# 11. Source Conflict Rules

If two sources appear to conflict:

### Step 1

Identify the exact claims.

### Step 2

Identify the authority of each source.

### Step 3

Check whether the sources are actually discussing the same concept.

### Step 4

Determine whether one statement describes:

* Scrum
* Agile
* a common practice
* an optional technique
* a course requirement
* a team convention

### Step 5

Explain the distinction.

### Step 6

State remaining uncertainty when necessary.

AgileFlow must not silently combine conflicting definitions.

---

# 12. Source Classification Model

AgileFlow should use this model:

```text
Scrum Guide 2020
      ↓
[SCRUM]

Agile Manifesto / Principles
      ↓
[AGILE]

Scrum.org supporting material
      ↓
[SUPPORTING]

Course requirements
      ↓
[COURSE]

Common Agile techniques
      ↓
[PRACTICE] / [OPTIONAL]

Team decisions
      ↓
[TEAM]

Information not established
      ↓
[UNKNOWN]
```

---

# 13. Knowledge File Relationship

The `knowledge/` directory converts the source material into focused topics for AgileFlow.

```text
knowledge/
├── 01-agile-foundation.md
├── 02-scrum-framework.md
├── 03-product-backlog.md
├── 04-user-stories.md
├── 05-acceptance-criteria.md
├── 06-sprint-workflow.md
├── 07-estimation.md
├── 08-quality-and-definition-of-done.md
├── 09-inspection-and-adaptation.md
├── 10-misconceptions-and-antipatterns.md
└── 11-agent-decision-rules.md
```

The knowledge files provide the operational guidance.

This source register identifies where the underlying framework information comes from.

---

# 14. Source-Grounded Response Rule

When answering a framework question, AgileFlow should prefer authoritative source-backed information.

Example:

```text
User:
"Does Scrum require story points?"

AgileFlow:
Story points are not a formal Scrum requirement.
They are a commonly used estimation practice.

Classification:
Story points → [OPTIONAL] / [PRACTICE]
```

AgileFlow should not change the classification simply because a particular team uses story points.

---

# 15. Practical Guidance vs Framework Rules

AgileFlow may provide practical recommendations, but it must distinguish them from framework requirements.

Use language such as:

> "A commonly used approach is..."

or:

> "Your team could..."

rather than:

> "Scrum requires..."

unless the claim is actually a formal Scrum requirement.

---

# 16. Final Source Rule

> Use authoritative sources for framework definitions, clearly classify complementary practices, preserve team and course context, and make uncertainty visible.

AgileFlow should prioritize accuracy over forcing a single Agile workflow.


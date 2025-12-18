# 00 — Theory Scope (Phase 2)

## Purpose

This document defines **what Phase 2 is allowed to contain** and, more importantly, **what it is not allowed to do**.

Phase 2 exists to enable disciplined reasoning without accidentally authorizing execution, optimization, or forward progress toward deployment.

If a reader can plausibly take an action after reading a document, that document does not belong in Phase 2.

---

## What Phase 2 *Is*

Phase 2 is a **reasoning sandbox**.

It is permitted to:

* Examine assumptions made in Phase 0 and Phase 1
* Stress-test boundary conditions
* Explore worst-case and failure-dominant scenarios
* Identify second-order and third-order effects
* Compare conceptual archetypes
* Ask "what if this fails silently?"
* Ask "what happens at the edges?"
* Identify where intuition is likely wrong

Phase 2 material may be uncomfortable, pessimistic, or deliberately over-conservative.

That is intentional.

---

## What Phase 2 *Is Not*

Phase 2 is **not** a bridge to execution.

It must **not**:

* Specify build instructions
* Provide dimensions, tolerances, or materials lists
* Define test setups or validation procedures
* Provide simulation parameters intended for implementation
* Describe optimization pathways
* Recommend design changes for performance improvement
* Include schedules, milestones, or readiness criteria
* Propose integration approaches
* Contain cost models tied to execution decisions

If a sentence answers *"what should we do next?"* — it does not belong here.

---

## Relationship to Other Phases

### Phase 0

Phase 0 defines **permission to exist**.

Phase 2 may question Phase 0 assumptions but may not redefine the mission, purpose, or non-claims.

If Phase 0 boundaries are wrong, that is noted — not fixed — in Phase 2.

---

### Phase 1

Phase 1 defines **permission to test**.

Phase 2 may:

* Question whether Phase 1 tests are sufficient
* Identify blind spots in validation logic
* Highlight scenarios Phase 1 intentionally ignores

Phase 2 may **not**:

* Expand Phase 1 scope
* Add new tests
* Modify success criteria
* Suggest test sequencing

---

## Legal Boundary

Phase 2 is governed by the **Theory Exploration License (TEL-1.0)**.

Nothing in Phase 2:

* Grants execution permission
* Waives execution licensing
* Alters Phase 0 or Phase 1 license terms

Any execution derived from Phase 2 reasoning requires a separate execution license defined in Phase 3.

---

## Allowed Language Patterns

Examples of acceptable phrasing:

* "If this assumption is false, the system likely degrades as follows…"
* "Under extreme conditions, failure could propagate via…"
* "This architecture is vulnerable to scenarios where…"
* "This trade favors simplicity at the expense of…"

---

## Prohibited Language Patterns

Examples of language that **does not belong** in Phase 2:

* "The system should be built using…"
* "Testing should be performed by…"
* "This could be validated by…"
* "To improve performance, change…"
* "The next step is…"

If wording implies action, it is out of scope.

---

## Interpretation Rule

When in doubt:

> If a reasonable engineer could act on it, it does not belong in Phase 2.

Phase 2 exists to **reduce the cost of thinking**, not to advance the project.

---

**End of Theory Scope Definition**

---
name: Behavior
about: A user-visible behaviour, with Given/When/Then acceptance criteria for a coding agent to implement test-first
title: "T00 · "
type: Behavior
---

<!-- Labels to add by hand or by the backlog tool:
     - exactly one lane label (lane:<name>): the agent work stream that executes this
     - one size label: size:S (1-2 files) or size:M (3-5 files); anything larger is split first
     - optionally one priority label: P0 must have, P1 should have, P2 could have
     The milestone is the phase of the plan this belongs to. -->

<!-- Title: the task number in execution order, then the behaviour in a few words,
     e.g. "T09 · Reset link expires after 30 minutes" -->

- **ID:** <!-- T00: plan letter and number, in execution order -->
- **Lane:** <!-- lane:<name> -->
- **Depends on:** <!-- task IDs or issue links that must be done first, or "none". Also set them as "blocked by" in the sidebar. -->
- **Source request:** <!-- the feature request this came from -->

## Story

As a <!-- kind of user -->
I want <!-- capability -->
So that <!-- benefit -->

## Acceptance criteria

<!-- 2 to 5 scenarios: the normal path, edge cases and failures.
     State intent, not clicks. Every Then names a concrete, observable outcome
     (a message, a status, a stored value). -->

### Scenario: <!-- name -->
- **Given** <!-- starting state -->
- **When** <!-- the action -->
- **Then** <!-- observable outcome -->
- **And** <!-- further outcome, if any -->

### Scenario: <!-- name -->
- **Given**
- **When**
- **Then**

## Present outcome

<!-- Only when this changes existing behaviour: what happens today. Delete the section otherwise. -->

- **But** at present,

## Out of scope

<!-- What this story deliberately does not cover. -->

-

## Technical notes

<!-- Grounded in the project brief: area of the code, data, interfaces, constraints. -->

-

## Open questions

<!-- Anything unclear in the request. A story with open questions is not ready to be worked. -->

None.

## How to work this story

1. Write a failing test for each scenario above, named after the scenario.
2. Run the tests and confirm they fail because the behaviour is missing, not because of a mistake in the test.
3. Implement the behaviour the scenarios describe, in general, not only for the example values in the tests. Do not hard-code expected results, special-case test inputs, or weaken, skip or delete a test to make it pass.
4. Stay within this story: nothing listed under Out of scope, and no unrelated refactoring.
5. Do not change the scenarios. If one is wrong, unclear or cannot be met properly, stop and ask on this issue instead of working around it.

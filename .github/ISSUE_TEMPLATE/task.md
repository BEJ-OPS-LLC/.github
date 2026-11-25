---
name: Task
about: Non-behavioural work (refactor, upgrade, infrastructure, performance) with a checklist of verifiable outcomes
title: "T00 · "
type: Task
---

<!-- Labels to add by hand or by the backlog tool:
     - exactly one lane label (lane:<name>): the agent work stream that executes this
     - one size label: size:S (1-2 files) or size:M (3-5 files); anything larger is split first
     - optionally one priority label: P0 must have, P1 should have, P2 could have
     The milestone is the phase of the plan this belongs to. -->

<!-- Title: the task number in execution order, then the outcome in a few words,
     e.g. "T14 · Upgrade the email library to v5" -->

- **ID:** <!-- T00: plan letter and number, in execution order -->
- **Lane:** <!-- lane:<name> -->
- **Depends on:** <!-- task IDs or issue links that must be done first, or "none". Also set them as "blocked by" in the sidebar. -->
- **Source request:** <!-- the feature request this came from -->

## Goal

<!-- One or two sentences: what changes and why. -->

## Verifiable outcomes

<!-- Each item must be checkable by running or reading something. -->

- [ ]
- [ ]

## Out of scope

<!-- What this task deliberately does not cover. -->

-

## Technical notes

<!-- Grounded in the project brief: area of the code, data, interfaces, constraints. -->

-

## Open questions

<!-- Anything unclear in the request. A task with open questions is not ready to be worked. -->

None.

## How to work this task

1. Where an outcome can be tested, write the failing test first and confirm it fails because the outcome is not met yet.
2. Achieve each outcome properly, not just the appearance of it. Do not hard-code results, special-case test inputs, or weaken, skip or delete a test or check to make it pass.
3. Tick an outcome only when you have verified it.
4. Stay within this task: nothing listed under Out of scope, and no unrelated refactoring.
5. If an outcome is wrong, unclear or cannot be met properly, stop and ask on this issue instead of working around it.

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

1. Where an outcome can be tested, write the failing test first and confirm it fails.
2. Make the smallest change that achieves the outcomes.
3. Tick an outcome only when you have verified it.
4. Do not widen the scope; if an outcome is wrong or unclear, stop and ask on this issue.

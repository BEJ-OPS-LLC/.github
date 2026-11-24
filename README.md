# BEJ-OPS-LLC organisation defaults

Issue templates in this repository are offered in every repository of the
organisation that has none of its own. It is public because GitHub only reads
organisation defaults from a public `.github` repository; it holds formats,
nothing else.

## The backlog format

Work is written as issues of three types:

| Type | Use | Shape |
|---|---|---|
| **Behavior** | A user-visible behaviour | One user story with 2 to 5 Given/When/Then scenarios |
| **Task** | Refactors, upgrades, infrastructure, performance | A checklist of verifiable outcomes |
| **Checkpoint** | The review gate at the end of a milestone | A checklist a person signs off |

Three words, used precisely:

- **Milestone**: a phase of a plan. A feature request is broken into milestones.
- **Lane**: one agent's work stream, the label `lane:<name>`. Every Behavior or Task issue has exactly one.
- **Swimlane**: a row on a project board, grouped by milestone or by lane.

Other conventions:

- Titles start with a task number in execution order: `T09 · Reset link expires after 30 minutes`.
- Size is a label: `size:S` is 1 to 2 files, `size:M` is 3 to 5. Larger work is split before it is filed.
- Priority, where used, is a label: `P0` must have, `P1` should have, `P2` could have.
- Dependencies are GitHub "blocked by" relationships.
- An issue with open questions is not ready to be worked.
- Agents work test-first and do not edit acceptance criteria; if one is wrong, they stop and ask on the issue.

The tooling that drafts and files these issues lives in a separate repository.

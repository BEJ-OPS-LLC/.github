---
name: Checkpoint
about: A review gate at the end of a milestone, closed by a person after review
title: "CP0 · "
type: Checkpoint
---

<!-- One checkpoint per milestone. It carries no lane label: it is the reviewer's, not an agent's.
     Set every issue in the milestone as "blocks" this one, and set this one as blocking the
     first tasks of the next milestone. -->

Review gate for milestone **<!-- milestone title -->**.

**A person closes this** after checking:

- [ ] Every issue in the milestone is closed, and its tests pass on the development branch
- [ ] The milestone's behaviour works end to end
- [ ] The next milestone has been reviewed and is ready to start

Agents never close a checkpoint, and never work around one: a task blocked by an open checkpoint waits.

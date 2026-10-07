---
name: luminol
description: Evidence-led Mystery investigation for expectation/reality gaps. Use whenever observed behavior differs from expected behavior, a proposed change lacks a proven cause, or a candidate change needs deterministic reproduction followed by later independent or live non-recurrence.
---

# Luminol

Close the gap between expectation and reality without hiding uncertainty behind
a quick patch. Until evidence establishes a mechanism, call the gap a
**Mystery**, preserve the surprise, and investigate before editing production
code.

## Investigation

1. Freeze the exact witness. Record expected behavior separately from observed
   behavior, including literal errors, exits, timestamps, rows, and physical
   observations.
2. Gather evidence already present in the repository, store, process tree,
   logs, and controlled fixtures. Add only the smallest telemetry needed to
   distinguish explanations.
3. Keep multiple plausible hypotheses alive. Name what evidence would
   strengthen, weaken, or distinguish each one.
4. Run the smallest discriminating tests. Preserve one deterministic
   reproduction that is red before the change.
5. Change the proven shared seam, not a reported symptom. Keep adjacent
   contracts green and avoid retries, parsers, state, or machinery unrelated to
   the demonstrated cause.
6. Mark the result `CANDIDATE` after deterministic proof. Mark it `RESOLVED`
   only after a later independent or live exercise of the original path records
   non-recurrence.

## Language

- Say **Mystery**, **expectation/reality gap**, **witness**, **hypothesis**,
  **discriminator**, and **candidate change** while the cause remains unknown.
- Do not prematurely call unexplained behavior a bug, broken implementation, or
  a person's mistake.
- Preserve literal failure evidence without euphemism. Once evidence proves the
  mechanism, name it precisely.
- Treat disconfirming evidence as progress. A disproven candidate narrows
  reality; it is not a reason to weaken the witness.

## Ownership

Whoever owns the requirements states expected product behavior and rules on
genuine product tradeoffs. The implementing team owns evidence collection,
telemetry, hypotheses, reproductions, and candidate changes. Gather evidence directly whenever tools can reach it.
Ask the human only for a physical-device, account, UI condition, or live
condition the workers cannot themselves run, and request the exact observation
or artifact needed.

Luminol is a reasoning discipline, not a tracked status, workflow gate,
permission system, retry policy, or excuse to build a new control plane.

Read [references/philosophy.md](references/philosophy.md) only when teaching the
method, helping a human collaborate with it, or writing public guidance.

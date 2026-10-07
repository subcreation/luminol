# Contributing To Luminol

Luminol should change only when a real Mystery record shows that its evidence
discipline misses, obscures, or prematurely narrows an expectation/reality gap.

## Useful Contributions

- A frozen Mystery with known mechanism and literal expected/observed witness.
- A reproducible case where a plausible patch lacked a proven seam.
- A smallest discriminating test or deterministic red reproduction.
- A classification or reproduction correction that preserves the accepted
  CANDIDATE and later non-recurrence boundary.
- Clearer documentation that does not change the frozen behavior.

## Before Opening A Pull Request

1. Start from the intended integration base on a feature branch.
2. Keep unrelated work out of the branch.
3. Preserve the exact expected and observed witness before proposing a cause.
4. Name competing hypotheses and the smallest discriminator for each change.
5. Keep the change CANDIDATE until later independent or live non-recurrence.
6. Run `git diff --check` and inspect the full base-to-head commit and path
   range.
7. Push the exact head and open a draft pull request.

Changes to `SKILL.md` or `references/philosophy.md` require a compatibility
decision and independent review. Do not turn Luminol into title grammar, a
parser, status machine, retry policy, permission layer, or workflow engine.

By submitting a contribution, you agree that it may be licensed under this
repository's Apache License 2.0.

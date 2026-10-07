# Luminol Philosophy

Luminol makes unexplained behavior interesting enough to investigate and hard
to paper over with confident, unproven code.

Blame and urgency pull a team toward the first plausible explanation. Curiosity
keeps competing explanations alive long enough to test them. The language is
therefore operational, not cosmetic: call an unexplained gap a Mystery until
evidence proves its mechanism.

## Human Collaboration

Invite the human to preserve what they saw, especially evidence workers cannot
reproduce: exact visible copy, sound, timing, device state, account state, or a
physical action. Ask a bounded question such as:

> What exact observation would help us tell these explanations apart?

Do not ask the human to repeat evidence the repository, message store, process
tree, logs, or a controlled fixture can provide.

## Language Examples

Before evidence:

- Avoid: "The implementation is broken."
- Prefer: "Expected all windows to notify; observed `event = null` in all four.
  The mechanism is not established yet."
- Avoid: "Fix the timeout."
- Prefer: "A timeout is one hypothesis. Preserve the live process and compare it
  with provider, process, and worktree evidence before changing the timer."

After evidence:

- Name the proven shared seam and the discriminating result.
- Keep literal exceptions, failed checks, and exit codes unchanged.
- Call the change `CANDIDATE` until the original path later exercises it without
  recurrence.

Luminol does not promise that Mysteries are pleasant or instantly solvable. It
promises that surprise, uncertainty, and disconfirmation remain visible until
reality supports a conclusion.

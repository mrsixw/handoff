---
name: handoff
description: Write a concise, redacted handoff document so another agent can continue the current work without replaying the conversation.
---

# Handoff

Create a continuation record that lets a fresh agent resume without replaying
the conversation. Prefer authoritative current state over a narrative history.

Write to the operating system's temporary directory unless the user specifies a
durable location. Redact tokens, credentials, personal data, and sensitive
payloads.

## Record the resumable state

Include:

- the requested outcome and authority boundary;
- repository path, branch, base, HEAD, and working-tree state where relevant;
- completed work and remaining scope;
- decisions, assumptions, and rejected alternatives that still matter;
- changed files and links to authoritative artefacts;
- an exact validation ledger, including checks not run;
- blockers, risks, and unresolved questions; and
- the next smallest action, with an exact command when safe and useful.

Name prerequisite or follow-on skills only when they materially affect the next
step. Reference existing evidence rather than copying large outputs. Do not
claim a remote mutation, clean tree, passing check, or resolved blocker without
verifying its current state.

Scale the record to the work. Omit sections with nothing material to preserve.

Completion means a fresh agent can tell what is true now, what remains, where
the evidence lives, and what action is authorised next.

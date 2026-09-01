---
name: handoff
description: Write a concise, redacted handoff document so another agent can continue the current work without replaying the conversation.
disable-model-invocation: true
---

# Handoff

Write the handoff to the operating system's temporary directory unless the user specifies another location.

Include the goal, current state, decisions, evidence paths, changed files, validation results, blockers, next action, and suggested skills. Reference existing artifacts instead of duplicating them. Redact secrets, tokens, and personal data.

Completion means a fresh agent can identify what is done, what remains, and where the authoritative evidence lives.

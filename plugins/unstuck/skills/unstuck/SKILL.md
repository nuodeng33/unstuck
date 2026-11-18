---
name: unstuck
description: Move stalled engineering work forward and finish the requested deliverable. Use when rereading, retries, or repeated reviews delay delivery, or when picking up an interrupted conversation, delegated work, or project history from a vector store.
license: MIT
---

# Unstuck

Use what the project already knows. Take the next action that advances the result the user asked for.

## Pick up where the work stopped

- Start with the user's latest direction, the session summary, and the project's existing handoff or work record. Open known files and artifacts directly. Check the facts that would change the next action.
- Reuse an established diagnosis, a reviewed patch, or a verification result that still applies. If a build, test, or delegated task is in flight, find its handle and check its state before starting another.
- When multiple agents contribute, integrate their diffs and evidence. Give each remaining task an owner and a concrete output. Review the issues that could change what ships.
- When project history is available through a vector store, look up the decision, artifact, or test result needed for the next action. Confirm it against the linked source, current revision, or output when it would change that action. Then proceed.
- If a later session will need a handoff, update the existing record. If there is none, leave one short note with the requested outcome, current branch or artifact, links to evidence, and the next action. Record active jobs or blockers when they affect the handoff.

## Finish the requested result

- Follow the user's ordering. Start with existing code and tools, cover the affected callers and compatibility, and complete the authorized steps that produce the requested result. A passing patch may still need a build or a package.
- Run checks that answer an open question about this result or satisfy a project requirement. Reuse a pass when the relevant version, inputs, and environment are still applicable. If the same attempt stops yielding evidence, change the hypothesis or move to the next actionable gap.
- Keep work on the user's result. When one step is blocked, advance independent work already in scope and state what is needed for the blocked step.
- Hand over the result once the required checks support it. Say what was implemented, what was verified, what was delivered, and anything still needed to use it. If the user already authorized a follow-up, continue after the agreed prerequisite is met.

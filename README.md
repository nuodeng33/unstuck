# Unstuck

**Shut up. Get back to work.**

Found the bug? Got a patch from another agent? Use what you have, take the next step, and finish the job.

One Agent Skill for Codex, Claude Code, and Google Antigravity.

[简体中文](README.zh-CN.md) · [Download Skill](https://github.com/nuodeng33/unstuck/releases/latest)

> Use Unstuck. The patch is in this checkout, and the regression test passed. Finish the release package.

If the earlier test still applies, build the package, check the artifact, and hand it over. When another retry or review would tell you nothing new, change the approach or move on to the work that's ready.

| When to use it | What to do next |
| --- | --- |
| **Pick up a long conversation** | Start from the latest instruction, the current patch, and the last recorded next step. |
| **Work with multiple agents** | Integrate their diffs and evidence. Check jobs already running and assign the parts still open. |
| **Look up history in a vector store** | Find the decision or result you need. Check its source when it changes the next step, then act on it. |

## Install

Extract the `unstuck` folder from the [Skill ZIP](https://github.com/nuodeng33/unstuck/releases/latest) into the skills directory for your client.

| Client | User skills directory | Invoke |
| --- | --- | --- |
| Codex | `~/.agents/skills/` | `$unstuck` |
| Claude Code | `~/.claude/skills/` | `/unstuck` |
| Google Antigravity | `~/.gemini/config/skills/` | `/unstuck` |

Codex also supports marketplace installation.

```sh
codex plugin marketplace add nuodeng33/unstuck
codex plugin add unstuck@unstuck-skills
```

In a new chat, invoke Unstuck and say what needs to be finished. Unstuck can use the vector search and agent tools you already have configured.

[MIT License](LICENSE)

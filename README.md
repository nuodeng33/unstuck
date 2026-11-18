# Unstuck

**Shut up. Get back to work.**

Found the bug? Got a patch from another agent? Use what you have, take the next step, and finish the job.

[简体中文](README.zh-CN.md) · [Download Skill](https://github.com/nuodeng33/unstuck/releases/latest)

> `$unstuck The patch is in this checkout, and the regression test passed. Finish the release package.`

If the earlier test still applies, Codex can build, check, and hand over the package. When another retry or review would tell you nothing new, use a different approach or move on to the work that's ready.

| When to use it | What to do next |
| --- | --- |
| **Pick up a long conversation** | Start from the latest instruction, the current patch, and the last recorded next step. |
| **Work with multiple agents** | Integrate their diffs and evidence. Check jobs already running and assign the parts still open. |
| **Look up history in a vector store** | Find the decision or result you need. Check its source when it changes the next step, then act on it. |

## Install

```sh
codex plugin marketplace add nuodeng33/unstuck
codex plugin add unstuck@unstuck-skills
```

In a new Codex chat, select the **Unstuck** skill and say what needs to be finished. For a standalone install, extract the `unstuck` folder from the Skill ZIP into `~/.agents/skills/` and invoke `$unstuck`. Unstuck can use the vector search and agent tools you already have configured.

[MIT License](LICENSE)

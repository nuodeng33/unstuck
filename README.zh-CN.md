# Unstuck

**闭嘴，接着干活。**

已经定位了就修，别人改完了就接手，验证过了就往下做。把用户要的东西交出来。

[English](README.md) · [下载 Skill](https://github.com/nuodeng33/unstuck/releases/latest)

> `$unstuck 补丁已在当前工作区，回归测试也过了。把发布包做出来。`

已有测试结果还适用于当前版本，就接着打包、检查产物并交付。同样的重试或复核给不出新信息，就换办法，或者先把能推进的部分做完。

| 什么时候用 | 接着做什么 |
| --- | --- |
| **续接长对话** | 从最新指令、已有补丁和上次留下的下一步接上。 |
| **多智能体协作** | 接手其他代理的改动和验证，确认在途任务，只分派还没做的部分。 |
| **用向量库查项目历史** | 找到下一步需要的决策或结果。会改变行动时，核对原始记录或产物版本，然后继续做。 |

## 安装

```sh
codex plugin marketplace add nuodeng33/unstuck
codex plugin add unstuck@unstuck-skills
```

新开 Codex 对话，选择 **Unstuck** 技能并说清要交付什么。也可以把 Skill ZIP 里的 `unstuck` 目录解压到 `~/.agents/skills/`，直接用 `$unstuck` 调用。向量检索和多智能体协作使用你已配置的工具。

[MIT 许可证](LICENSE)

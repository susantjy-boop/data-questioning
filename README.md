# data-questioning：数据提问教练

把日常看数据、追问、做决策的步骤写成一个 skill，帮你在拿出结论之前，先把该追问的问题问一遍。

## 安装

**Claude Code**：

```bash
git clone https://github.com/susantjy-boop/data-questioning.git ~/.claude/skills/data-questioning
```

**Codex**：

```bash
git clone https://github.com/susantjy-boop/data-questioning.git ~/.codex/skills/data-questioning
```

不用命令行的话：在仓库页面点「Code → Download ZIP」，解压后把文件夹改名为 `data-questioning`，放进 `~/.claude/skills/`（Codex 放进 `~/.codex/skills/`）。

更新到最新版：`git -C ~/.claude/skills/data-questioning pull`

装好后重新打开对话即可。说"帮我看下这个数据""这张表有什么问题""交付前帮我检查"等，会自动触发；也可以直接说"用 data-questioning"。

## 文件说明

只有一个文件 `SKILL.md`，包含：看数据 → 追问 → 做决策三阶段、十层问题、汇报原则、提问卡、交付前自查清单，以及文末的业务包模板。

## 三种常见用法

1. **带着一张表来**："帮我看看这张表有哪些问题，怎么优化。"
2. **带着一个决定来**："这个达人还值不值得继续寄样？"
3. **交付前自查**："我写好了分析，发出去之前帮我检查一遍。"

做某个业务时，先让 skill 带你按文末的业务包模板建一份 `业务包-<业务名>.md`，放在 `SKILL.md` 旁边。

## 注意

公开版只保留通用方法和业务包模板，不含任何具体业务的口径、人名或数据。

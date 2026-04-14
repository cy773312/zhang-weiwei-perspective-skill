# 张维为视角 Skill（zhang-weiwei-perspective）

这是一个可直接用于 Codex 的人物思维 Skill，聚焦复旦大学教授张维为的分析框架。

## 功能

- 用“文明型国家/中国模式”视角分析国际议题
- 内置 5 个核心心智模型与 8 条决策启发式
- 包含可执行的回答工作流（Agentic Protocol）
- 附带六维调研底稿（著作、对话、表达DNA、他者评价、决策记录、时间线）

## 目录结构

- `SKILL.md`：主技能文件
- `references/research/`：调研与提炼文档

## 使用方式

将本目录放到本地 Codex skills 目录下，例如：

```bash
~/.codex/skills/zhang-weiwei-perspective
```

重启 Codex 后，可通过以下表达触发：

- 「张维为怎么看这个问题」
- 「用 zhang weiwei perspective 分析」
- 「用文明型国家视角重算一次」

## 来源说明（重要）

本 Skill 的构建方法与流程**基于 [nuwa-skill](https://github.com/alchaincyf/nuwa-skill)** 的「女娲造人术」框架执行，已按该流程完成目录化调研、框架提炼与质量校验。

- 上游项目：`alchaincyf/nuwa-skill`
- 本仓库为该方法在“张维为人物蒸馏”任务上的落地实现

## 许可与声明

- 本仓库用于学习、研究与提示词工程实践。
- 人物观点基于公开资料提炼，不代表本人实时立场。

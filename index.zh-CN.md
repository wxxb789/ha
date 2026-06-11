# Index — 按 area 与 target 索引

> [English](./index.md) · **简体中文**

仓库**按类型**组织（就是那些目录）。每个逻辑 artifact 在这里也占**一行**，用
`areas` 和 `targets` 打标签——因为一个 artifact 常同时服务多个 area 或 runtime，
而目录表达不了这一点。

## 标签词表

```text
areas:    software-development | work-management | self-management
targets:  runtime-agnostic | repo-only |
          claude-code | codex | opencode | hermes | pi | kimi-code
```

- 两个轴都**可多值**（逗号分隔）。
- **type** 从顶层目录推导——不要重复打标。
- `targets` = 这个 skill 用 `npx skills --agent` 装到哪些 runtime
  （`runtime-agnostic` = 任意；`repo-only` = 永不下发，如库 / 知识类）。
- 一行对应一个**逻辑** artifact（不为双语文件分别建行）。
- 暂不设 `status` 轴，等实验 / 废弃状态真的出现再加。

## 编目

目前手工维护；Phase 3 可从 per-artifact metadata 生成。

| Artifact | Type | Areas | Targets | Path | Notes |
|---|---|---|---|---|---|
| _(示例)_ commit-push-pr | skill | software-development | runtime-agnostic | `skills/commit-push-pr/` | git commit / PR 流程 |
| _(示例)_ plan-execute-verify | orchestration | software-development | repo-only | `orchestration/plan-execute-verify.md` | 控制模式;verify → retry |
| _(示例)_ oracle | agent | software-development | repo-only | `agents/oracle.md` | 只读推理角色 |
| _(示例)_ weekly-review | workflow | self-management, work-management | repo-only | `workflows/weekly-review.md` | 周五 retro + 下周计划 |

> 标 _(示例)_ 的行是占位——有真实 artifact 时替换掉。

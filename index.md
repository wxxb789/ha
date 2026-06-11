# Index — artifacts by area & target

> **English** · [简体中文](./index.zh-CN.md)

The repo is organized **by type** (the folders). Every logical artifact also
gets **one row here**, labeled by `areas` and `targets` — because one artifact
often serves several areas or runtimes, and folders can't express that.

## Label vocabulary

```text
areas:    software-development | work-management | self-management
targets:  runtime-agnostic | repo-only |
          claude-code | codex | opencode | hermes | pi | kimi-code
```

- Both axes are **multi-valued** (comma-separated).
- **Type** is derived from the top-level folder — don't re-label it.
- `targets` = which `npx skills --agent` a skill installs to (`runtime-agnostic`
  = any; `repo-only` = never deployed, e.g. library/knowledge types).
- One row per **logical** artifact (not one per bilingual file).
- No `status` axis until experimental / deprecated states actually appear.

## Catalog

Hand-curated for now; Phase 3 may generate it from per-artifact metadata.

| Artifact | Type | Areas | Targets | Path | Notes |
|---|---|---|---|---|---|
| _(example)_ commit-push-pr | skill | software-development | runtime-agnostic | `skills/commit-push-pr/` | git commit / PR flow |
| _(example)_ plan-execute-verify | orchestration | software-development | repo-only | `orchestration/plan-execute-verify.md` | control pattern; verify → retry |
| _(example)_ oracle | agent | software-development | repo-only | `agents/oracle.md` | read-only reasoning role |
| _(example)_ weekly-review | workflow | self-management, work-management | repo-only | `workflows/weekly-review.md` | Friday retro + next-week plan |

> _(example)_ rows are placeholders — replace them as real artifacts land.

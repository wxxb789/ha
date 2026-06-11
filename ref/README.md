# ref — External references

> **English** · [简体中文](./README.zh-CN.md)

A curated map of agent / skill / harness repos worth learning from. This is
**not vendored code** — just where I go for inspiration and patterns to steal.
When something here proves its worth, adapt it into the matching top-level folder —
[`../skills/`](../skills/), [`../orchestration/`](../orchestration/),
[`../agents/`](../agents/), … (keep attribution).

## How to add

Append a row below. Make **"What to steal"** concrete — name the specific idea,
pattern, or file worth taking, not just "good repo".

| Repo | Category | What to steal | Link |
|---|---|---|---|
| _(example)_ VoltAgent/awesome-agent-skills | skills index | curated directory to mine for skill ideas | <https://github.com/VoltAgent/awesome-agent-skills> |
| _(example)_ kepano/obsidian-skills | skills | clean `SKILL.md` authoring style | <https://github.com/kepano/obsidian-skills> |

> Rows marked _(example)_ are starters — replace them with your own picks.

## Optional: vendoring

If you want a reference's code locally, add it as a git submodule under
`ref/<name>/`. Prefer links — submodules inflate the repo and pull in someone
else's history. Never copy code that carries a secret or a personal path.

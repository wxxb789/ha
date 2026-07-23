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

## Vendored references (submodules)

All rows below are cloned locally as git submodules under `ref/<name>/`, each
**branch-tracking** its upstream default branch. Refresh every one to latest:

```sh
git submodule update --remote --merge   # pull all tracked branches to their latest
```

| Repo | Category | What to steal | Link |
|---|---|---|---|
| EveryInc/compound-engineering-plugin | eng skills | compounding-engineering skill set — each unit of work makes the next easier | <https://github.com/EveryInc/compound-engineering-plugin> |
| EveryInc/compound-knowledge-plugin | knowledge skills | knowledge-work equivalent of compound engineering; workflows that compound | <https://github.com/EveryInc/compound-knowledge-plugin> |
| obra/superpowers | methodology | full agent dev methodology built on composable skills + bootstrap instructions | <https://github.com/obra/superpowers> |
| mattpocock/skills | eng skills | daily real-engineering skills (not vibe coding) authoring style | <https://github.com/mattpocock/skills> |
| juliusbrussee/caveman | prose | terse "caveman" prose mode; multi-agent (30+) skill/plugin packaging | <https://github.com/juliusbrussee/caveman> |
| JimLiu/baoyu-skills | skills | Baoyu's skill collection | <https://github.com/JimLiu/baoyu-skills> |
| JimLiu/baoyu-design | design | Claude Design running on any file-capable coding agent | <https://github.com/JimLiu/baoyu-design> |
| lijigang/ljg-skills | skills | ljg skill pack + install-via-`skills` conventions | <https://github.com/lijigang/ljg-skills> |
| zjp1997720/zhijian-skills | skills | eleven focused skills: Codex ops, workflow orchestration, model infra, knowledge | <https://github.com/zjp1997720/zhijian-skills> |
| fattly/god-skill | skills | god-skill patterns | <https://github.com/fattly/god-skill> |
| dontbesilent2025/dbskill | biz skills | Chinese AI skills toolkit for founders/creators; judgment + execution output | <https://github.com/dontbesilent2025/dbskill> |
| tw93/Waza | eng habits | each engineering habit → an installed slash-command skill (Claude Code + Codex) | <https://github.com/tw93/Waza> |
| tw93/Kami | design | typeset pro docs & landing pages (resumes, one-pagers, white papers) | <https://github.com/tw93/Kami> |
| lyra81604/zhengxi-views | views | zhengxi views patterns | <https://github.com/lyra81604/zhengxi-views> |
| ksimback/looper | orchestration | looper control-loop patterns | <https://github.com/ksimback/looper> |
| kunchenguid/no-mistakes | workflow | push-to-`no-mistakes` disposable-worktree AI validation pipeline before forwarding | <https://github.com/kunchenguid/no-mistakes> |
| kunchenguid/gnhf | workflow | "never wake up empty-handed" overnight-work pattern | <https://github.com/kunchenguid/gnhf> |
| kunchenguid/lavish-axi | artifacts | HTML-as-markdown editor for HTML artifacts | <https://github.com/kunchenguid/lavish-axi> |
| petergyang/no-ai-slop | prose | edit drafts sharper/more human while preserving voice; detect AI-slop patterns | <https://github.com/petergyang/no-ai-slop> |
| mvanhorn/last30days-skill | search | upvote/like/money-scored agent-led search engine skill | <https://github.com/mvanhorn/last30days-skill> |
| titanwings/colleague-skill | meta-skill | distill a colleague/relationship/celebrity persona into a reusable skill | <https://github.com/titanwings/colleague-skill> |
| alchaincyf/nuwa-skill | meta-skill | Nuwa skill-generation patterns | <https://github.com/alchaincyf/nuwa-skill> |
| notdog1998/yourself-skill | meta-skill | distill *yourself* from chat/diaries/photos into a runnable digital self | <https://github.com/notdog1998/yourself-skill> |
| YIKUAIBANZI/forge-skill | meta-skill | distill a person's persona from chat logs/moments into a chatting archetype | <https://github.com/YIKUAIBANZI/forge-skill> |
| alchaincyf/huashu-design | design | HTML high-fidelity prototypes/slides/animation + 3-direction draft rule | <https://github.com/alchaincyf/huashu-design> |
| yaojingang/yao-open-skills | skills | open skill pack + Skill Doctor config-safety diagnostics | <https://github.com/yaojingang/yao-open-skills> |
| yaojingang/yao-open-prompts | prompts | open-source practical-work prompt library | <https://github.com/yaojingang/yao-open-prompts> |
| yaojingang/yao-meta-skill | meta-skill | build/improve/eval skills from workflows/SOPs/scripts; routing + install checks | <https://github.com/yaojingang/yao-meta-skill> |
| virattt/dexter | agent | autonomous financial research agent: task planning, self-reflection, real data | <https://github.com/virattt/dexter> |
| taxueseek/say-it-human | prose | "is there a real person behind your text" humanizing checks (zh) | <https://github.com/taxueseek/say-it-human> |
| blader/humanizer | prose | humanizer rewriting patterns | <https://github.com/blader/humanizer> |
| op7418/Humanizer-zh | prose | Chinese humanizer variant | <https://github.com/op7418/Humanizer-zh> |
| MrGeDiao/shuorenhua | prose | "说人话" — strip AI cliché from zh/en text, flag-problem-first rewriting | <https://github.com/MrGeDiao/shuorenhua> |
| Leonxlnx/taste-skill | design | upgrade AI-built UIs: layout, typography, motion, spacing over boilerplate | <https://github.com/Leonxlnx/taste-skill> |
| affaan-m/ECC | skills | multi-language ECC skill set | <https://github.com/affaan-m/ECC> |
| multica-ai/andrej-karpathy-skills | skills | Karpathy-style skills; Multica agent/skill-sharing platform patterns | <https://github.com/multica-ai/andrej-karpathy-skills> |
| garrytan/gstack | review | sequential CEO/design/eng/DX auto-review pipeline with decision principles | <https://github.com/garrytan/gstack> |
| anthropics/skills | skills | Anthropic's canonical `SKILL.md` structure and examples | <https://github.com/anthropics/skills> |
| victorchen96/victorchen96.github.io (`auto_research/`) | research | auto-research framework; single self-contained `SKILL.md` paper-writing flow | <https://victorchen96.github.io/auto_research/framework.html> |
| anthropics/knowledge-work-plugins (`finance/`) | plugins | role-specialist plugins for Claude Cowork; finance close/reconciliation/SOX | <https://github.com/anthropics/knowledge-work-plugins> |

> Two rows are subdirectories of a larger repo — the whole repo is vendored;
> look under the path in parentheses (`auto_research/`, `finance/`).

## Adding more

Add a reference as a branch-tracking submodule so it can be refreshed to latest:

```sh
git submodule add -b <default-branch> <url> ref/<name>
git submodule set-branch --branch <default-branch> ref/<name>   # if -b was omitted
```

Prefer links over vendoring when you only need the idea — submodules inflate the
repo and pull in someone else's history. Never copy code that carries a secret
or a personal path.

# panviva Claude Code Plugins

Marketplace manifest for Upland Software Claude Code plugins.

## Setup (one-time)

```
/plugin marketplace add panviva/upland-marketplace
```

## Install plugins

```
/plugin install burnrate-claude --scope user
/plugin install skillforge --scope user
/plugin install upld-git-skills --scope user
/plugin install sangt-daily-mandatory-skills --scope user
/plugin install memory-management-skills --scope user
/plugin install upld-modernisation-skills --scope user
/plugin install pv-legacy-skills --scope user
```

## Available plugins

| Plugin | Description |
|--------|-------------|
| `burnrate-claude` | Real-time AWS Bedrock cost in the statusline |
| `skillforge` | Enterprise AI skill library for team skill management |
| `upld-git-skills` | Git & release workflow skills (commit-message, pr-checklist, changelog-entry) — install the bundle, new skills arrive via `/plugin marketplace update` (no reinstall) |
| `sangt-daily-mandatory-skills` | Daily-driver session skills (start-my-day, multi-model plan-for-goal with Gemini 3.8 / GPT-5.6 / Kimi 3, project-setup, session-start, session-handoff, session-calibrate) — a full cross-session workflow |
| `memory-management-skills` | Memory & knowledge-base skills (karpathy-obsidian-memory-setup) — set up an LLM-maintained Obsidian knowledge base |
| `upld-modernisation-skills` | Panviva modernisation skills — evidence-backed implementation-readiness audit of a PANV epic or story with every claim source-cited (pv-modernisation-readiness-audit), plus **always-on** C# `///` XML documentation enforcement shipping its own checker script and pre-commit hook (panviva-xml-docs, and panviva-xml-docs-copilot for Copilot users) |
| `pv-legacy-skills` | Panviva Core (legacy SupportPoint) skills — **always-on** production-incident investigation grounded in New Relic telemetry across the C# web tier, the SPIL modules and the C++ `mentord` appserver, which also validates or corrects an RCA someone else wrote (panviva-prod-investigation, contributed by Tristan, ships its `nrql.sh` helper) |

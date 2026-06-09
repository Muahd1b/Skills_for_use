# Repo-local Codex Skills

This folder contains a curated copy of official Codex skills for use inside this repository.

Scope:
- Included: built-in `.system` skills and official OpenAI-curated/plugin skills copied from the local Codex installation.
- Excluded: personal/custom skills from `~/.codex/skills/*`, `~/.agents/skills/*`, and other user-created skill folders.

Why this set:
- The repo is data and operations heavy, so the copy focuses on analytics, documents, spreadsheet/report work, browser control, GitHub workflows, and knowledge/document connectors.
- The goal was to bring in the most useful official baseline, not every available Codex/plugin skill.

Included skill groups:

## `system`
- `imagegen`
- `openai-docs`
- `plugin-creator`
- `skill-creator`
- `skill-installer`

Source:
- `~/.codex/skills/.system/`

## `browser`
- `control-in-app-browser`

Source:
- `~/.codex/plugins/cache/openai-bundled/browser/.../skills/`

## `github`
- `github`
- `gh-fix-ci`
- `gh-address-comments`

Source:
- `~/.codex/plugins/cache/openai-curated/github/.../skills/`

## `google-drive`
- `google-drive`
- `google-docs`
- `google-sheets`
- `google-slides`

Source:
- `~/.codex/plugins/cache/openai-curated/google-drive/.../skills/`

## `notion`
- `notion-knowledge-capture`
- `notion-research-documentation`
- `notion-spec-to-implementation`

Source:
- `~/.codex/plugins/cache/openai-curated/notion/.../skills/`

## `data-analytics`
- `index`
- `analyze-data-quality`
- `build-dashboard`
- `build-report`
- `design-kpis`
- `gather-business-context`
- `jupyter-notebooks`
- `kpi-reporting`
- `market-sizing`
- `metric-diagnostics`
- `product-business-analysis`
- `user-context`
- `validate-data`
- `visualize-data`

Source:
- `~/.codex/plugins/cache/openai-curated-remote/data-analytics/.../skills/`

## `runtime`
- `documents`
- `presentations`
- `spreadsheets`

Source:
- `~/.codex/plugins/cache/openai-primary-runtime/.../skills/`

Total copied skills: `33`

Notes:
- The copied folders include each skill's `SKILL.md` plus any bundled scripts, references, and templates that came with the source directory.
- If you want, this can be expanded later with official Figma, Gmail, Calendar, Sales, or Product Design skills, but those were intentionally left out of the first pass.

# Repo-local Codex Skills

- Include only built-in `.system` and official OpenAI-curated/plugin skills copied from the local Codex installation; exclude personal/custom skills.
- Preserve each copied skill’s `SKILL.md` and bundled scripts, references, and templates.
- Collection additions or source/provenance changes: read [README.md](README.md).

## File size

- Keep every source file at or below 500 LOC. Tests, docs and CSS are exempt. Markdown is documentation, not source. Split a source file before completion if your change takes it over the limit.
- Hooks activate automatically on managed development accounts and new Codex environments. Pre-commit checks only staged authored text: at most 5,000 tokens (bytes / 4). See [.githooks/README.md](.githooks/README.md) for generated-file exemptions and splitting instructions.

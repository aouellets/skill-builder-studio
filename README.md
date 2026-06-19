# Skill Builder Studio

**Author, test, and curate Claude Agent Skills with confidence** — built in-house by [Skill&nbsp;Me](https://skillme.dev).

A meta-pack for engineers and prompt designers who build Claude Agent Skills. Covers the full authoring lifecycle: writing skills, crafting discoverable descriptions, testing trigger accuracy, converting prompts into skills, and curating coherent packs.

⭐ **If this is useful, star the repo** — it's how we gauge what to build next.

## Install

- **From the catalog:** [skillme.dev/pack/skill-builder-studio](https://skillme.dev/pack/skill-builder-studio) — install the whole pack into Claude in one step.
- **With the skills CLI:** `npx skills add aouellets/skill-builder-studio`
- **Manually:** copy any `skills/<slug>/SKILL.md` into your Claude skills directory.

## Skills in this pack

- **[Skill Author](skills/skill-author/SKILL.md)** — Writes a high-quality Claude Agent Skill (SKILL.md) from a capability idea.
- **[Skill Description Writer](skills/skill-description-writer/SKILL.md)** — Writes discoverable skill descriptions (what + when, third person) that trigger reliably.
- **[Skill Tester](skills/skill-tester/SKILL.md)** — Tests a skill with subagent scenarios to verify it triggers correctly and performs its job.
- **[Prompt to Skill](skills/prompt-to-skill/SKILL.md)** — Converts a repeated prompt or workflow into a reusable SKILL.md.
- **[Skill Pack Curator](skills/skill-pack-curator/SKILL.md)** — Curates a coherent pack or bundle of skills by resolving persona vs workflow conflicts and enforcing overlap limits.
- **[Prompt Engineer](skills/prompt-engineer/SKILL.md)** — Writes structured prompts with role, context, format, and examples for any LLM task.
- **[MCP Server Builder](aouellets)** — Builds MCP servers with proper tool definitions, error handling, and auth patterns. _(external — see source)_

## License

MIT — see [LICENSE](LICENSE). Skills are portable `SKILL.md` files; the canonical
copies live in the [Skill&nbsp;Me catalog](https://skillme.dev).

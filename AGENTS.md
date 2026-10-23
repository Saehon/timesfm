# TimesFM — Agent Entry Point

This repository ships a first-party **Agent Skill** for TimesFM at:

```
timesfm-forecasting/
└── SKILL.md    ← read this for the full skill
```

## Install the skill

Copy the skill directory into your agent's skills folder:

```bash
# Cursor / Claude Code / OpenCode / Codex (global install)
cp -r timesfm-forecasting/ ~/.cursor/skills/
cp -r timesfm-forecasting/ ~/.claude/skills/

# Or project-level
cp -r timesfm-forecasting/ .cursor/skills/
```

Any agent that supports the open [Agent Skills standard](https://agentskills.io) will discover it automatically.

## Working in this repo

If you are developing TimesFM itself (not using it), the source lives in `src/timesfm/`.
Archived v1/v2 code and notebooks are in `v1/`.

Run tests:

```bash
pytest v1/tests/
```

See `README.md` for full developer setup.

<!-- PSEUDOCODE-SYSTEMS-THINKING v1 -->
## Pseudocode and systems thinking

Before material research or implementation work, read `RESEARCH_METHOD.md` and the nearest project instructions. Define the system boundary and write/update numbered pseudocode before changing the relevant workflow. Map material steps to actual implementation, independent checks and output evidence. Use `research-method/contract.template.json` without treating a completed template as verified execution. For a trivial edit, update only the affected step or note why the algorithm is unchanged. Preserve project-specific permissions, pauses, scientific results, attribution and release rules. Apply this method to all subprojects, keeping each project's own sources, algorithm and evidence record separate.
<!-- END PSEUDOCODE-SYSTEMS-THINKING -->

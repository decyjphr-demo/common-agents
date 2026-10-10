# common-agents

Central repository of team prompt files, skills, and custom agents.

## Authoring rules
- Skills: the frontmatter `name` must match the directory name (lowercase, hyphens).
- Skills: the `description` must say when to use the skill ("Use when...").
- Skills: link to files in `scripts/`, `references/`, and `assets/`; don't paste their content.
- Skills: no links to files outside the repository, and no committed archives (`.zip`).
- Agents: always set `tools` to the minimum required set.
- Agents: the `description` says what the agent does and when to use it, not a persona.
- Prompts: use `${input:name:placeholder}` for variables.
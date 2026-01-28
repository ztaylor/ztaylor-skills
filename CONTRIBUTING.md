# Contributing

This is a personal collection of Claude Code skills. I'm not actively seeking new skill submissions, but PRs for bug fixes, typos, or improvements to existing skills are welcome.

## Reporting Issues

If you find a problem with a skill—unclear instructions, broken workflows, or incorrect information—please open an issue or submit a PR.

## Forking This Repo

If you want to create your own skills collection, feel free to fork. Here's the structure:

```
skills/
└── your-skill-name/
    ├── SKILL.md              # Required: The main skill file
    └── references/           # Optional: Supporting files
```

### SKILL.md Format

Every skill needs a `SKILL.md` with YAML frontmatter:

```yaml
---
name: your-skill-name
description: |
  When to use this skill. Include trigger phrases that help Claude
  know when this skill is relevant.
invocation: explicit
---
```

The body should include:

- **Role Definition** - What expertise Claude should embody
- **Process** - Step-by-step workflow
- **Output Specifications** - What gets created and where

### Tips for Good Skills

- **Be opinionated.** Encode best practices, don't just list options.
- **Be specific.** Include concrete examples and expected outputs.
- **Preserve context.** For multi-document outputs, use subagents to avoid context degradation.

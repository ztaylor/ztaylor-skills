# ztaylor-skills

A collection of Claude Code skills by [Zachary Taylor](https://github.com/ztaylor)

## What Are Skills?

Skills are markdown files that give AI agents specialized knowledge and workflows for specific tasks. When you invoke a skill, Claude Code and other AI agents gain deep expertise in that domain and follow proven methodologies to deliver comprehensive results.

## Available Skills

### idea-consultant

Transform any business or product idea into a comprehensive development framework with expert consultation documents.

**What it does:**

- Asks clarifying questions about budget, timeline, and constraints
- Generates an exhaustive checklist of everything you need to figure out
- Creates deep-dive expert consultation documents for each relevant area
- Synthesizes everything into an executive summary with verified consistency

**Invoke with:** `/idea-consultant`

---

## Installation

```bash
npx skills add ztaylor/ztaylor-skills --skill idea-consultant
```

<details>
<summary>Alternative installation methods</summary>

### Claude Code Plugin

```bash
claude /plugin:add https://github.com/ztaylor/ztaylor-skills
```

### Clone and Copy

```bash
git clone https://github.com/ztaylor/ztaylor-skills.git
cp -r ztaylor-skills/skills/* ~/.claude/skills/
```

</details>

## Usage

Once installed, invoke any skill by typing its command:

```
/idea-consultant
```

Claude will guide you through the process.

## Creating Your Own Skills

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines on creating and submitting new skills.

## License

MIT - See [LICENSE](LICENSE) for details.

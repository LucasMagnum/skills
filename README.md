# skills

A starter Claude Code plugin template.

## Install

```bash
npx skills add lucasmagnum/skills
```

Or install from the Claude marketplace plugins.

## What's Included

| Component | Path | Description |
|-----------|------|-------------|
| Command | `commands/hello.md` | `/hello` slash command |
| Skill | `skills/example-skill/SKILL.md` | Auto-triggered example skill |
| Agent | `agents/helper.md` | Research helper subagent |

## Project Structure

```
skills/
├── .claude-plugin/
│   └── plugin.json        # Plugin manifest (required)
├── commands/               # Slash commands (auto-discovered .md files)
│   └── hello.md
├── skills/                 # Skills (auto-discovered SKILL.md in subdirs)
│   └── example-skill/
│       └── SKILL.md
├── agents/                 # Subagents (auto-discovered .md files)
│   └── helper.md
├── LICENSE
└── README.md
```

## Customization

1. Edit `.claude-plugin/plugin.json` with your name, repo, and description
2. Add/modify commands in `commands/`
3. Add/modify skills in `skills/<skill-name>/SKILL.md`
4. Add/modify agents in `agents/`
5. Optionally add `hooks/hooks.json` for event hooks
6. Optionally add `.mcp.json` for MCP server integrations

## License

MIT

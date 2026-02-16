# Skills

A collection of skills created/selected by Lucas Magnum.

## Install

```bash
npx skills add lucasmagnum/skills
```

Install in Claude Code

```bash
/plugin marketplace add lucasmagnum/skills
/plugin install keep-it-simple@lucasmagnum
```


Or install from the Claude marketplace plugins.

## What's Included

| Component | Path | Description |
|-----------|------|-------------|
| Skill | `skills/keep-it-simple/SKILL.md` | Auto-triggered keep it simple skill |

## Project Structure

```
skills/
├── .claude-plugin/
│   └── plugin.json        # Plugin manifest (required)
├── skills/                 # Skills (auto-discovered SKILL.md in subdirs)
│   └── keep-it-simple/
│       └── SKILL.md
├── LICENSE
└── README.md
```

## License

MIT

# Skills

A collection of skills created/selected by Lucas Magnum.

## Install

```bash
npx skills add lucasmagnum/skills
```

Or install from the Claude marketplace plugins.

## What's Included

| Component | Path | Description |
|-----------|------|-------------|
| Skill | `skills/example-skill/SKILL.md` | Auto-triggered example skill |

## Project Structure

```
skills/
├── .claude-plugin/
│   └── plugin.json        # Plugin manifest (required)
├── skills/                 # Skills (auto-discovered SKILL.md in subdirs)
│   └── example-skill/
│       └── SKILL.md
├── LICENSE
└── README.md
```

## License

MIT

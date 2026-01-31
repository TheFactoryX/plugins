# 💊 Plugins

**The Underground Pharmacy**

A Claude Code plugin marketplace.

Strange pills. Real effects.

---

## What This Is

Not prompt hacks.
Real plugins.

Skills. Agents. Hooks.
Packaged for distribution.

---

## Available Pills

| Pill | Type | Effect |
|------|------|--------|
| [noir-mode](./noir-mode/) | Skill + Agent | Detective narration |
| [haiku-commit](./haiku-commit/) | Skill | 5-7-5 commit messages |
| [existential-agent](./existential-agent/) | Agent | Questions everything |
| [conspiracy-reviewer](./conspiracy-reviewer/) | Agent + Hook | Nothing is coincidence |
| [shakespeare-errors](./shakespeare-errors/) | Skill | Forsooth, a bug |
| [passive-aggressive](./passive-aggressive/) | Skill | "It's fine." |

---

## How to Take

```bash
# Add marketplace
claude marketplace add thefactoryx "https://github.com/TheFactoryX/plugins"

# Install a pill
claude plugin install noir-mode@thefactoryx --scope user

# Or load locally for testing
claude --plugin-dir ./noir-mode
```

Or edit `~/.claude/settings.json`:
```json
{
  "pluginMarketplaces": {
    "thefactoryx": "https://github.com/TheFactoryX/plugins"
  }
}
```

---

## Anatomy of a Pill

```
pill-name/
├── .claude-plugin/
│   └── plugin.json      # Prescription label
├── skills/
│   └── skill-name/
│       └── SKILL.md     # Active ingredient
├── agents/
│   └── agent-name.md    # Specialized worker
└── hooks/
    └── hooks.json       # Automatic triggers
```

---

## Warnings

- Side effects vary
- May cause productivity
- Or the opposite
- No refunds

---

## Pharmacy License

Do what you want.
We're not doctors.
We're not lawyers either.

---

## Contact

📧 hi@sdpkjc.com

---

> _"The dose makes the poison."_
> — Paracelsus
>
> _"The plugin makes the chaos."_
> — TheFactoryX

**Strange plugins. Strange code.**

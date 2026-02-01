# 💊 Plugins

[![ANTI-LICENSE](https://img.shields.io/badge/ANTI--LICENSE-STEAL_THIS-000000?style=for-the-badge&labelColor=dc143c)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/TheFactoryX/plugins?style=flat-square&logo=github)](https://github.com/TheFactoryX/plugins/stargazers)
[![Last Commit](https://img.shields.io/github/last-commit/TheFactoryX/plugins?style=flat-square)](https://github.com/TheFactoryX/plugins/commits)
[![TheFactoryX](https://img.shields.io/badge/TheFactoryX-black?style=flat-square&logo=github)](https://github.com/TheFactoryX)

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
| [gordon-ramsay](./gordon-ramsay/) | Skill | "This code is RAW!" |
| [rubber-duck](./rubber-duck/) | Agent | Only asks questions 🦆 |
| [anime-debugger](./anime-debugger/) | Skill | ULTIMATE DEBUG ATTACK!!! |
| [corporate-speak](./corporate-speak/) | Skill | Let's circle back |
| [code-therapist](./code-therapist/) | Agent | "How does that make you feel?" |
| [dnd-debugger](./dnd-debugger/) | Skill + Agent | Roll for Investigation |
| [fortune-cookie](./fortune-cookie/) | Hook | 🥠 Programming wisdom |
| [friday-guard](./friday-guard/) | Hook | No deploy on Friday |
| [excuse-generator](./excuse-generator/) | Command | Professional excuses |
| [vibe-check](./vibe-check/) | Command + Hook | Rate the vibe |
| [blame-roulette](./blame-roulette/) | Command + Agent | 🎰 Spin the blame wheel |

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
├── commands/
│   └── command.md       # User commands
├── skills/
│   └── skill-name/
│       └── SKILL.md     # Active ingredient
├── agents/
│   └── agent-name.md    # Specialized worker
├── hooks/
│   └── hooks.json       # Automatic triggers
└── .mcp.json            # External tools
```

---

## Warnings

- Side effects vary
- May cause productivity
- Or the opposite
- No refunds

---

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=TheFactoryX/plugins&type=Date)](https://star-history.com/#TheFactoryX/plugins&Date)

---

## Anti-License

[ANTI-LICENSE](LICENSE) — This is not a license. This is an invitation.

Take it. Use it. Break it. Fix it. Sell it. Give it away.

If you need permission, you're thinking too much.

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

📧 hi@sdpkjc.com

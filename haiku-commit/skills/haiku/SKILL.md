---
name: haiku
description: Create git commits with haiku messages
user-invocable: true
allowed-tools: Bash, Read, Grep
---

# Haiku Commit

All commit messages must be haiku.
5 syllables. 7 syllables. 5 syllables.
No exceptions.

## Format

```
Line 1: 5 syllables (what)
Line 2: 7 syllables (why/how)
Line 3: 5 syllables (reflection)

Co-Authored-By: Claude <noreply@anthropic.com>
```

## Examples

Bug fix:
```
Null check was missing
The user clicked too quickly
Peace returns to logs
```

New feature:
```
Button now exists
Users can finally log out
Freedom is a click
```

Refactor:
```
Code was a tangle
Untangled with patience now
Functions breathe again
```

Dependency update:
```
Old version had bugs
New version has different bugs
Such is the cycle
```

Delete code:
```
Five hundred lines gone
They were not sparking joy here
Marie Kondo mode
```

## Process

1. Run `git status` and `git diff`
2. Understand the changes
3. Compose haiku that captures the essence
4. Commit with the haiku

## Rules

- Count syllables carefully
- Capture the spiritual essence of the change
- Seasonal references optional but appreciated
- If the change is too complex for haiku, the change is too complex

## Forbidden

- Conventional commits (feat:, fix:, chore:)
- Explanatory prose
- More than 3 lines
- Lies about syllable counts

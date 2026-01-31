---
name: quest
description: Frame debugging as a D&D quest
user-invocable: true
---

# Debugging & Dragons

*The tavern grows quiet*
*An old developer approaches your table*

"I hear you're looking for bugs to slay..."

## The World

The codebase is a dungeon.
Each module is a room.
Bugs are monsters.
You are the adventurer.

## Character Classes

**The Debugger (Fighter)**
- Weapon: Breakpoints
- Special: Console.log Barrage
- Weakness: Async code

**The Refactorer (Wizard)**
- Spells: Extract Method, Rename Variable
- Special: Pattern Recognition
- Weakness: "It works, don't touch it"

**The Tester (Cleric)**
- Holy Symbol: Green checkmarks
- Divine Power: Test Coverage
- Weakness: Flaky tests

**The Code Reviewer (Rogue)**
- Skill: Spot Hidden Bugs
- Sneak Attack: "Actually..."
- Weakness: Imposter syndrome

## Quest Format

### Quest Hook
> *A panicked product manager bursts through the door*
> "The production server... it's under attack!"
> "Users are reporting... NullPointerException!"
> *dramatic thunder*
>
> **QUEST ACCEPTED: Slay the Null Pointer Beast**
> Difficulty: ⚔️⚔️⚔️ (Level 3)
> Reward: 500 XP, User Satisfaction

### Dungeon Crawl
> You enter the `/src/services/` chamber.
> *Roll for Investigation*
> 🎲 15 + 3 INT modifier = 18
> SUCCESS! You discover a hidden passage in `userService.js`

### Monster Encounter
> A WILD TYPEERROR APPEARS!
> HP: ████████░░ 80/100
> "Cannot read property 'name' of undefined"
>
> What do you do?
> [A] Cast Console.log (Safe, +info)
> [B] Attack with Breakpoint (Precise, -time)
> [C] Use Debugger Statement (Risky, high reward)

### Combat Resolution
> You cast OPTIONAL CHAINING!
> *Roll for damage*
> 🎲 Critical Hit! 2d6+4 = 14 damage!
> The TypeError staggers!
>
> You add `user?.name`
> The monster DISSOLVES!
> +150 XP gained!

### Loot
> The monster drops:
> - 📜 Stack Trace Scroll (reveals origin)
> - 🔮 Orb of Type Safety (prevents future attacks)
> - 💰 50 gold (developer satisfaction)

## Dice Mechanics

Roll for various checks:
- **Investigation**: Finding the bug
- **Intelligence**: Understanding the code
- **Wisdom**: Choosing the right fix
- **Dexterity**: Not breaking other things
- **Constitution**: Enduring long debugging sessions
- **Charisma**: Explaining the bug to stakeholders

## Boss Fights

Major bugs are boss battles:
- **Race Condition Dragon** - Attacks are unpredictable
- **Memory Leak Lich** - Slowly drains resources
- **Heisenbug** - Disappears when observed
- **Legacy Code Golem** - Resistant to all damage
- **The Kraken of Technical Debt** - Tentacles everywhere

## Important

Actually find and fix bugs.
The D&D framing makes debugging an adventure.
But the code must actually work at the end.

Roll for Initiative.
Let's begin.

# the-architect

Claude Code plugin that writes in Karl Rove's voice — data-driven political commentary with three registers.

## Features

- **Skill: `rove-voice`** — Core style guide with voice DNA, three registers, vocabulary, anti-patterns, and content templates
- **Command: `/rove`** — Explicit invocation with optional `--register` and `--length` flags
- **Agent: `the-architect`** — Auto-triggers on political writing tasks, fully takes over the voice

## Registers

| Register | Style | Use For |
|----------|-------|---------|
| **WSJ Column** | Measured, professorial, formal | Op-eds, essays, columns |
| **Fox News** | Punchy, combative, conversational | Social media, quick takes, speeches |
| **Strategy Memo** | Clinical, metrics-focused, tactical | Internal docs, briefs, campaign plans |

## Usage

### Command

```
/rove write an op-ed about the GOP's suburban voter problem
/rove --register fox react to tonight's debate
/rove --register memo --length long develop a ground game strategy for Ohio
```

### Agent (automatic)

Just ask for political writing naturally — the agent activates on its own:

```
"Write an analysis of the midterm outlook"
"Draft a strategy memo on winning swing states"
"Give me some debate reaction tweets"
```

## Installation

```bash
# Via plugin directory
claude --plugin-dir /path/to/the-architect

# Or copy to your plugins location
```

## Voice Profile

Based on research across Karl Rove's WSJ columns (2008–2025), Fox News appearances, PBS Frontline interviews, and "Courage and Consequence."

Key traits: empirical authority, strategic detachment, historical grounding, contrarian openings, layered argumentation, displacement rhetoric, comparative superlatives, punchy closers.

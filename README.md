# the-architect

Claude Code plugin that writes about Malaysian politics in Karl Rove's voice — data-driven, strategically detached, historically grounded commentary.

## Features

- **Skill: `rove-voice`** — Core style guide with voice DNA, three registers, Malaysian political vocabulary, anti-patterns, and content templates
- **Command: `/rove`** — Write in Rove's voice with optional `--register` and `--length` flags
- **Command: `/guide`** — Interactive guide to plugin capabilities
- **Agent: `the-architect`** — Auto-triggers on Malaysian political writing tasks, fully takes over the voice

## Registers

| Register | Style | Use For |
|----------|-------|---------|
| **Column** | Measured, professorial, formal | Op-eds, essays, columns |
| **Pundit** | Punchy, combative, conversational | Social media, quick takes, speeches |
| **Strategy Memo** | Clinical, metrics-focused, tactical | Internal docs, briefs, campaign plans |

## Usage

### Command

```
/rove write an op-ed about why GPS is the real kingmaker
/rove --register pundit react to PAS sweeping Kelantan
/rove --register memo --length long strategy for defending Selangor
```

### Agent (automatic)

Just ask for Malaysian political writing naturally:

```
"Write an analysis of the GE16 outlook for PH"
"Draft a strategy memo on breaking through in Johor"
"Give me some tweets reacting to the PRN results"
```

### Guide

```
/guide           # Full overview
/guide registers # Register details
/guide voice     # Voice DNA explanation
```

## Installation

```bash
# Test locally
claude --plugin-dir /path/to/the-architect

# Or install from GitHub
/plugin marketplace add truthwatcher-ai/the-architect
/plugin install the-architect@the-architect
```

## Voice Profile

Karl Rove's style applied to Malaysian politics:
- Empirical authority (seat counts, swing margins, DOSM data)
- Strategic detachment (chess-match framing)
- Historical grounding (GE14, GE15, Sheraton Move, Perak 2009)
- Contrarian openings, layered argumentation, punchy closers

Covers all 222 parliamentary seats, state DUN assemblies, key coalitions (PH, PN, BN, GPS, GRS), and Malaysia's multiethnic electoral dynamics.

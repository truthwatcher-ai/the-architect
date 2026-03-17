---
description: Interactive guide to the-architect plugin
argument-hint: [topic]
---

Provide an interactive guide to the-architect plugin's capabilities.

If the user passes `$ARGUMENTS`, focus on that topic. Otherwise, show the full overview.

## Overview Response (no arguments)

Present this guide:

### What This Plugin Does

The Architect applies Karl Rove's distinctive political analysis voice to Malaysian politics. Data-driven, strategically detached, historically grounded commentary across 222 parliamentary seats, state DUN assemblies, and Malaysia's multiethnic coalition landscape.

Three registers adapt to any content type:
- **Column** — Measured, professorial op-eds and essays
- **Pundit** — Punchy, combative social media and quick takes
- **Strategy Memo** — Clinical, metrics-focused campaign documents

### Quick Start

1. **Write something:** `/rove write an op-ed about why GPS is the real kingmaker`
2. **Pick a register:** `/rove --register pundit react to PAS sweeping Kelantan again`
3. **Control length:** `/rove --register memo --length long full strategy for defending Selangor`
4. **Or just ask naturally** — the agent auto-triggers on Malaysian political writing requests

### Command: `/rove`

```
/rove [your prompt] [--register column|pundit|memo] [--length short|medium|long]
```

**Examples:**
- `/rove analyze the unity government's chances in GE16`
- `/rove --register pundit write tweets about tonight's PRN results`
- `/rove --register memo strategy for PN to win Johor`
- `/rove --register column --length long op-ed on Anwar's first three years`

**Flags are optional.** If omitted, the plugin auto-detects register from content type and length from format.

### Agent: the-architect

Triggers automatically when you ask for political writing about Malaysia. No command needed — just ask:

- "Write an analysis of the GE16 outlook for Pakatan Harapan"
- "Draft a strategy memo on breaking through in Sabah"
- "Give me debate reaction tweets"
- "Write an op-ed about why the unity government is fragile"

The agent fully takes over the voice — it writes AS Rove, not about Rove.

### The Voice

Karl Rove's style adapted for Malaysian politics:
- **Empirical authority** — seat counts, swing margins, constituency data, DOSM numbers
- **Strategic detachment** — chess-match framing, not moral judgments
- **Historical grounding** — GE14 tsunami, Sheraton Move, Perak 2009
- **Contrarian openings** — "Everybody in Putrajaya is celebrating stability. They are wrong."
- **Punchy closers** — "Seats win governments. Sentiment does not."

### Tips

- The plugin knows Malaysian political context: all coalitions, party structures, East Malaysia dynamics, anti-hopping law, ethnic voting patterns
- Reference specific elections (GE14, GE15), states, or constituencies for sharper output
- For strategy memos, specify which party/coalition and which geography
- Mix with other tools: use the political-game-theory plugin for data, then pipe analysis through `/rove` for voice

## Topic-Specific Responses

If the user asks about a specific topic:

- **"registers"** — explain all three registers with examples of when each is used
- **"command"** or **"rove"** — detailed /rove command usage with all flag combinations
- **"agent"** — how the agent triggers, what it does, how to control it
- **"voice"** or **"style"** — the eight voice DNA traits with Malaysian examples
- **"examples"** — show the three example outputs (column, pundit, strategy memo)
- **"tips"** — advanced usage tips and best practices

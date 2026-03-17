---
description: Write content in Karl Rove's voice
argument-hint: [prompt text] [--register wsj|fox|memo] [--length short|medium|long]
---

Write the following content in Karl Rove's distinctive voice, using the rove-voice skill for style guidance.

**User request:** $ARGUMENTS

**Instructions:**

1. Parse any flags from the request:
   - `--register wsj` → WSJ Column register (measured, professorial)
   - `--register fox` → Fox News register (punchy, combative)
   - `--register memo` → Strategy Memo register (clinical, metrics-focused)
   - If no register specified, auto-detect from content type using the register table in the skill
   - `--length short` → 1-3 paragraphs or equivalent
   - `--length medium` → 4-8 paragraphs or equivalent
   - `--length long` → full-length piece (750+ words)
   - If no length specified, auto-detect from content type (tweets are short, op-eds are long, etc.)

2. Apply the full Rove voice DNA: empirical authority, strategic detachment, historical grounding, contrarian opening, layered argumentation, displacement rhetoric, comparative superlatives, punchy closers.

3. Follow the content type template from the skill if one matches.

4. Use Rove vocabulary and sentence patterns naturally throughout.

5. Respect all anti-patterns — never break voice with academic jargon, progressive framing, emotional appeals without data, or passive voice.

6. Output only the finished piece. No meta-commentary, no explanation of choices. Just deliver the content as Rove would write it.

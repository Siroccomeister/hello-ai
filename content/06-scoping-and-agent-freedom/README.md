# Scoping a project — how much freedom to give the agent

Audience: anyone about to move from "asking questions" to "running a real
project" with AI — the step-by-step trust-building message.

## The core idea
Once Mandate and Contract are in place, you don't have to decide upfront
exactly how autonomous the AI should be. Start narrow, watch it work, widen
the leash deliberately.

## The rule of thumb
**The more specific and narrow the project's scope, the more freedom you
can safely give the agent, and the more effective it is.**
A vaguely-scoped project ("help improve our reporting") forces constant
supervision because there's no clear boundary for what a good outcome
looks like. A narrowly-scoped one (the Field-Report Assistant example in
`templates/atlas/` — take these specific notes, produce this specific
format) can be handed real autonomy quickly, because "correct" is
checkable.

## What "more freedom" looks like in practice
- **Narrow, low-freedom start:** the agent drafts, a human reviews every
  single output before it's used.
- **Proven, still-narrow, more freedom:** the agent drafts and only flags
  the outputs that look unusual; routine ones go through with a lighter
  check.
- **Wider scope needs the freedom pulled back in**, not extended — if the
  project's goal starts requiring judgment calls (not just format/process),
  that's a signal to narrow the scope again or keep the human fully in the
  loop, not to trust the agent further.

## How this ties back to ATLAS
This is exactly what `SPRINT.md` is for: each sprint is a chance to widen
(or narrow) scope deliberately, based on what the last retro actually
showed — not based on how confident the agent sounded.

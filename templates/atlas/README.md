# ATLAS — a lightweight framework for AI-assisted projects

ATLAS is not a tool, it's a folder convention: files that keep an
AI-assisted project honest over time — anchored to a goal, aware of its own
contract, and able to show real progress instead of drifting into whatever
the last conversation happened to produce.

**Mandate → Contract → State → Sprint** (Sprint is optional — it can just be
a live working session instead of a formally tracked cadence; the other
three are not optional).

| File | Answers | Cadence |
|------|---------|---------|
| `MANDATE.md` | Why does this project exist, for whom, what does "done" mean? | Written once, revisited only on real scope change |
| `CONTRACT.md` | What are we bound by — security, privacy, tools/MCP servers, what we must never do? | Written once, updated when a new tool/data source enters |
| `STATE.md` | What's actually true today — progress, learnings, backlog? | Updated continuously, every session |
| `SPRINT.md` *(optional)* | What are we doing *right now*? Can be a live session instead. | Rewritten every sprint, if you're running sprints at all |
| `RETRO.md` | What did we learn last sprint/session; keep the same course or correct? | End of every sprint, or just on a regular interval |

## These templates are illustrative, not blank
Every file in this folder is filled in with a real worked example — a
small, fictional "Field-Report Assistant" project — so you can see what a
*good* Mandate or Contract actually looks like before writing your own.
Don't copy the example content; copy the shape and level of specificity.

## How to start a new project with it
1. Copy this `templates/atlas/` folder into your project repo, drop the
   `.template` suffix from each filename, and replace the worked example
   with your own project.
2. Fill in `MANDATE.md` first — if you can't state the goal in a paragraph,
   don't start yet.
3. Fill in `CONTRACT.md` before connecting any tool, MCP server, or data
   source to an AI session on this project.
4. Start `STATE.md` on day one and update it as you go — not at the end.
   This is what lets a session next week (or a teammate, or a fresh AI
   session with no memory of today) pick the project back up without
   re-deriving context.
5. If the work benefits from sprint structure, write `SPRINT.md` for what's
   in front of you right now, scoped small enough to actually finish. If
   not, a live working session is fine — just still retro it.
6. Retro on a regular cadence regardless — end of sprint, or just every
   couple of weeks. Write `RETRO.md`, decide if course needs correcting,
   keep going.

## Why this prevents drift
The failure mode ATLAS is built against isn't "the AI got something wrong,"
it's a project slowly wandering away from its own mandate one convenient
conversation at a time, with no contract check and no record of why past
decisions were made. Mandate gives it a fixed point. Contract keeps it from
overreaching. State makes progress legible instead of tacit. A retro
cadence forces a check on drift instead of one that never happens because
there was never a checkpoint to trigger it — see
`content/07-drift-and-retros/` for why this matters especially in long AI
conversations.

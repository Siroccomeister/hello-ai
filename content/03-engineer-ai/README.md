# Tier 3 — Engineering AI (Claude Code, real projects)

Audience: engineers and technical staff working directly in HT's codebases
and infrastructure.

## Talking points
- **Claude Code operates on your actual repo** — reads real files, runs real
  commands, proposes real diffs. The upside is it can do multi-step work
  end to end; the downside is mistakes are real mistakes, so review before
  approving anything destructive or shared (pushes, deletes, migrations).
- **CLAUDE.md is how you make it a good teammate on *this* repo** —
  conventions, architecture notes, what not to touch, where the danger
  zones are. Write it like onboarding a new hire, not like documentation.
- **This connects directly to ATLAS** (`content/05-atlas-framework/`): a
  Claude Code session run against a project with a MANDATE, BOUNDARIES, and
  live STATE stays on-track across many sessions instead of re-deriving
  context (or drifting) every time.
- **MCP servers at this tier** carry the same access-scope rule as Tier 2's
  connectors, but now with tools that can also *write* — a database MCP
  server, a deploy tool, an internal API. Boundaries file matters more, not
  less, here.
- **Trust but verify:** an AI-written diff, test suite pass, or agent's
  summary describes what it *attempted* — check the actual change before
  calling a task done, same as reviewing a junior engineer's PR.

## Live demo idea
Show a small real fix in an HT repo end-to-end: CLAUDE.md context → prompt →
diff review → test run → commit. Emphasize the review step, not the speed.

## Privacy note for this tier
Same trust boundary as normal engineering practice — never commit secrets,
follow the repo's own data-handling rules, treat local API calls as the
security boundary (not a special AI exception).

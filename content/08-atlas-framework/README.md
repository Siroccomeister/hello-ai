# The ATLAS framework

Where this session ties everything together: how to run an AI-assisted
*project*, not just a single AI *conversation*, without it drifting.

## The four pieces — Mandate → Contract → State → Sprint
- **Mandate** — the fixed goal. Written once, rarely touched.
- **Contract** — security, privacy, and tool/MCP-server rules; what this
  project is not allowed to do, and what it commits to (see the enterprise
  AI charter in `content/05-enterprise-charter/`).
- **State** — the living record: progress, learnings, backlog. Updated
  continuously so any session (a teammate, or a fresh AI session with zero
  memory) can pick the work back up without re-deriving context.
- **Sprint** — *optional, can be a live session* — what we're doing right
  now, scoped small enough to finish. Not every project needs formal
  sprints; all of them need Mandate, Contract, and State.
- **Retro** — the checkpoint, at the end of a sprint or simply at a regular
  interval, that either confirms course or corrects it. See
  `content/07-drift-and-retros/` — this is the piece that catches drift
  before it compounds.

## Why "drift" is the thing this is built against
Without a mandate, scope wanders toward whatever the last convenient
conversation produced. Without a contract, a connector or MCP server gets
attached without anyone asking what it exposes. Without live state, every
session re-derives context from scratch (or worse, contradicts the last
one). Without a retro cadence, nothing ever gets corrected — it just quietly
degrades.

## How to start today
Point people at `templates/atlas/README.md` — copy the folder into any
repo. The templates are filled with a worked example, not just blank
placeholders, so it's clear what "good" looks like before you write your
own. Fill in Mandate and Contract before the first real session.

## Where AI-first tooling (Claude Code) fits
Once a project has ATLAS files in the repo, an engineering-tier AI session
can read them directly — MANDATE.md and CONTRACT.md become the same kind
of onboarding material for an AI session as for a new hire. This is the
loop: ATLAS keeps the project legible, and that legibility is exactly what
lets AI tooling contribute safely and consistently across many sessions.

# State — hello-ai

_Last updated: 2026-08-28_

## Phase
Published: repo live at github.com/Siroccomeister/hello-ai, Pages live at
helloai.atarigo.net. Deck tightened to 8 slides with a defined red line;
not yet rehearsed.

## Progress
- 2026-08-28 — Repo scaffolded: MANDATE, STATE, BOUNDARIES, SPRINT,
  `templates/atlas/`, `content/` tier outlines, `docs/` reveal.js deck
  skeleton.
- 2026-08-28 — Restructured per feedback: Boundaries renamed to Contract
  throughout (Mandate → Contract → State → optional Sprint); templates
  rewritten as a worked illustrative example instead of blank placeholders;
  added four new content sections — `00-why-ai-now` (adoption-shift hook,
  3 sourced hard facts), `05-enterprise-charter` (training/retention
  toggles, subscription quotas vs. API, ZDR reality), `06-scoping-and-agent-
  freedom` (narrow scope → more agent freedom), `07-drift-and-retros` (long-
  conversation drift, retro cadence); `docs/index.html` rebuilt to match
  the new session order.

## Progress (cont.)
- 2026-08-28 — Committed, pushed to `github.com/Siroccomeister/hello-ai`
  (public), GitHub Pages enabled on `docs/` (main), custom domain
  `helloai.atarigo.net` confirmed live via CNAME DNS record.
- 2026-08-28 — Tone/format pass per feedback: deck cut from ~9 nested
  sections (40+ actual slides) down to a flat **8 slides**, one keyword
  idea each, simple inline-SVG icon per slide, a persistent chapter
  breadcrumb for the red line, and full talking points moved into
  `<aside class="notes">` speaker notes rather than on-screen. Added
  `content/DECK-MAP.md` documenting the through-line (Africa
  leapfrog-moment framing: mobile money/phones past legacy infra, AI is
  the next one). `content/00`–`09` kept as full-depth prep material,
  unchanged in content, now explicitly secondary to the on-screen deck.

## Learnings
- The three "hard facts" for the opening hook needed a live web search
  rather than memory — model knowledge cutoff (Jan 2026) is stale enough
  relative to the session date that self-reported stats risked being wrong;
  each fact now carries its source link in `content/00-why-ai-now/`.
- A first content pass tends to over-produce (nested reveal.js sections
  ballooned slide count well past what's presentable live) — worth
  designing the on-screen slide count and red line explicitly before
  writing section content, next time, rather than after.

## Backlog
- [ ] Fill in HT-specific examples per content tier (real workflows: field
  ops queries, loan/credit scoring analysis, dev work on HT's own repos) —
  still generic/fictional (the Field-Report Assistant), works for templates
  but the live talk would land harder with a real HT example.
- [ ] Rehearse timing with the new 8-slide deck — target session length
  TBD; check whether speaker notes are enough to talk to or need a printed
  fuller script.
- [ ] Decide if templates get a short live walkthrough (e.g. filling one out
  on stage) or just handed out.
- [ ] Post-session retro — log what landed, what to cut/keep for next time
  (see `templates/atlas/RETRO.template.md`).

## Notes
- The presenter's own relationship to HT (investor, not an HT employee) is
  deliberately kept out of this repo's content and files — it's
  session-delivery context, not something the public repo/slides need to
  carry. Keep future edits consistent with that.

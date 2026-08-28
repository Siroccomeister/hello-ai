# State — hello-ai

_Last updated: 2026-08-28_

## Phase
Content drafting for the Nairobi all-hands session. Repo skeleton and
first-pass content outlines created; nothing rehearsed or published yet.

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

## Learnings
- The three "hard facts" for the opening hook needed a live web search
  rather than memory — model knowledge cutoff (Jan 2026) is stale enough
  relative to the session date that self-reported stats risked being wrong;
  each fact now carries its source link in `content/00-why-ai-now/`.

## Backlog
- [ ] Fill in HT-specific examples per content tier (real workflows: field
  ops queries, loan/credit scoring analysis, dev work on HT's own repos).
- [x] ~~Confirm HT's actual AI vendor/plan tier~~ — confirmed 2026-08-28:
  no corporate AI setup exists at HT (early-stage startup), some staff use
  Claude on individual/personal accounts. `content/05-enterprise-charter/`
  now written against this reality rather than assuming a corporate plan
  to confirm.
- [x] ~~Draft a separate one-page interim AI guideline~~ — not needed: the
  deck itself *is* the guideline (confirmed 2026-08-28); the session closes
  by handing attendees a working quickstart prompt instead of a document.
- [x] Add closing "quickstart prompt" — `content/09-quickstart-prompt/` and
  matching deck slide, using confirmed GitHub owner `Siroccomeister`.
- [ ] Flesh out `docs/index.html` slide-by-slide from the `content/`
  outlines (still placeholder-level detail per slide vs. full script).
- [ ] git init first commit, create GitHub repo `hello-ai` under
  `Siroccomeister` (public), publish Pages, point `helloai.atarigo.net` at
  it (CNAME already in `docs/CNAME`).
- [ ] Rehearse timing — target session length TBD.
- [ ] Decide if templates get a short live walkthrough (e.g. filling one out
  on stage) or just handed out.
- [ ] Post-session retro — log what landed, what to cut/keep for next time
  (see `templates/atlas/RETRO.template.md`).

## Notes
- The presenter's own relationship to HT (investor, not an HT employee) is
  deliberately kept out of this repo's content and files — it's
  session-delivery context, not something the public repo/slides need to
  carry. Keep future edits consistent with that.

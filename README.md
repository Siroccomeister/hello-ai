# hello-ai

AI best-practices and guidelines for Hello Tractor — content for the Nairobi
all-hands, and a reusable framework (**ATLAS**) for running AI-assisted
projects that stay on-mandate over time.

- **Session deck:** [helloai.atarigo.net](https://helloai.atarigo.net) —
  reveal.js, built from `docs/index.html`. Deliberately just **8 slides**,
  one keyword idea each — the full script for each is in the slide's
  speaker notes (press `s` while presenting) and in `content/`.
- **Bootstrap page:** [helloai.atarigo.net/bootstrap](https://helloai.atarigo.net/bootstrap)
  — a page written *to* an AI assistant rather than a human: fetch it,
  read the templates it points to, and set up a new ATLAS project. Also
  published as plain text at
  [`/llms.txt`](https://helloai.atarigo.net/llms.txt) (the emerging
  `llms.txt` convention). This is what the closing quickstart prompt
  actually points at.
- **The red line:** [`content/DECK-MAP.md`](content/DECK-MAP.md) — maps
  each of the 8 slides to its backing `content/` material and states the
  through-line in one breath.
- **Talk content, full depth:** [`content/`](content/) — why this matters
  now (adoption shift), everyday chat use, builder tools
  (Projects/artifacts/connectors), engineering use (Claude Code), privacy,
  the enterprise AI charter, project scoping/agent freedom, staying on
  track (drift/retros), the ATLAS framework itself, and a closing
  [quickstart prompt](content/09-quickstart-prompt/) attendees can paste
  into any AI chat to bootstrap their own project on the spot.
- **Reusable project framework:** [`templates/atlas/`](templates/atlas/) —
  copy this folder into any repo to start an AI-assisted project with a
  Mandate, Contract, live State, and (optionally) a Sprint/Retro cadence
  from day one. Filled with a worked example, not blank placeholders.

This repo runs on its own framework — see [`MANDATE.md`](MANDATE.md),
[`CONTRACT.md`](CONTRACT.md), [`STATE.md`](STATE.md), and the current
[`SPRINT.md`](SPRINT.md).

## Publishing
GitHub Pages serves `docs/` on the `main` branch. Custom domain
`helloai.atarigo.net` is set via `docs/CNAME` once DNS is pointed at it.

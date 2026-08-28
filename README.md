# hello-ai

AI best-practices and guidelines for Hello Tractor — content for the Nairobi
all-hands, and a reusable framework (**ATLAS**) for running AI-assisted
projects that stay on-mandate over time.

- **Session deck:** [helloai.atarigo.net](https://helloai.atarigo.net) —
  reveal.js, built from `docs/index.html`.
- **Talk content, in session order:** [`content/`](content/) — why this
  matters now (adoption shift), everyday chat use, builder tools
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

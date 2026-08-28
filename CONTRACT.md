# Contract — hello-ai

## Repo-level
- This repo is **public** (GitHub Pages at `helloai.atarigo.net`). Nothing
  Hello Tractor-confidential — no customer data, no internal financials, no
  unreleased product detail, no real credentials/API keys/MCP tokens — goes
  into this repo, its history, or the published slides. Examples in the deck
  use fictional or clearly-illustrative data only.
- Treat every commit as permanently public, including after a later
  force-push or delete (GitHub history / forks / caches persist).

## Privacy tiers to teach in the session
Map tools to what's safe to put in them — this is the core "privacy is a
key matter" message for the all-hands:

| Tier | Tool | Safe to paste in |
|------|------|-------------------|
| Everyday chat | claude.ai / Gemini web, no connectors | Public or already-shareable info only. Nothing a customer, partner, or HR record would identify. |
| Builder | Projects/artifacts, connectors (Drive, Gmail, etc.) | Whatever the connected account can already see — connecting a source exposes its *full* scope, not just the one file you meant to use. Get data-owner sign-off before connecting anything with customer or financial data. |
| Engineering | Claude Code against a real repo | Follow the repo's own data rules; never commit secrets/`.env`; treat local API calls as the trust boundary — same model as normal engineering practice, not a special AI exception. |

## MCP servers — what to say
- An MCP server is a *connector*: it gives the assistant read (sometimes
  write) access to a real system for the duration of a session. It is not a
  one-off upload — the assistant can query anything the server's
  credentials can reach.
- Before connecting a server, know: what data is behind it, who owns that
  data, and whether this session is an appropriate place for it to be
  visible.
- Prefer scoped/read-only tokens over broad admin credentials when setting
  one up.

## Enterprise AI charter — what this project commits to
- No confidential HT content goes into a consumer-tier AI account where the
  vendor's terms allow storing it or using it for model training. Every
  workspace/account used for this project has training-use and
  indefinite-retention **toggled off** — that's a setting to check, not an
  assumption.
- Where genuine zero-retention is required, that's an API-tier
  conversation (cost, contracting), not something a standard chat
  subscription grants by default — see `content/05-enterprise-charter/`.

## Approval gate
- Any step that publishes something outward-facing (first GitHub push,
  enabling Pages, pointing the custom domain) — confirm before doing it,
  don't just do it because a template file says so.

## Reference
- HT does not currently have a company-wide AI usage / data handling
  policy (confirmed 2026-08-28 — early-stage startup, no corporate AI
  setup yet). This repo's session doubles as the first draft of guidance
  HT can adopt — see `content/05-enterprise-charter/`.

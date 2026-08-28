# Cross-cutting — Privacy

This is the thread that runs through all three tiers, not a bolt-on at the
end. Repeat the core rule at each tier rather than saving it for one slide.

## The core rule
**Ask what tier of tool you're in, and match the data to it.**

| Tier | Tool | Safe to include |
|------|------|-------------------|
| Everyday | claude.ai / Gemini, no connectors | Anything you'd put in a shared team doc. Nothing about a specific customer, employee, or unreleased number. |
| Builder | Projects/artifacts + connectors | Whatever the connected account can already see, and no more — connecting a source exposes its *full* scope. Get the data owner's sign-off first. |
| Engineering | Claude Code / MCP servers | Whatever the repo/system already trusts a local engineer with. No secrets in commits. |

## Why this matters specifically for connectors/MCP
The most common mistake is treating a connector like a single file upload.
It isn't — it's a standing grant of whatever that credential can reach for
the life of the session. The fix is not "don't use connectors," it's
"know the scope before you connect."

## What to tell people to actually do
- If unsure whether something is safe to paste: don't, ask first.
- Prefer read-only/scoped credentials over admin ones when setting up a
  connector or MCP server.
- Treat AI chat history like you'd treat a shared drive folder, not like a
  private notebook — assume it could be reviewed.

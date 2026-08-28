# Enterprise readiness — the AI charter

Audience: everyone, but especially anyone with a company AI subscription
seat or approval authority. The message: adoption is easy to start and easy
to get wrong quietly — the enterprise needs to be prepared, not just
enthusiastic.

## Where HT likely stands today
This is normal for an early-stage company, and worth saying plainly rather
than assuming otherwise: there is probably no company-wide AI plan, no
admin console, no written policy. People who use AI tools (and some already
do, e.g. Claude) are almost certainly doing so on **individual, personal
accounts** — which means whatever that vendor's consumer-tier defaults are
(training use, retention) already apply to anything typed in, with no
company-level visibility or control. That's not a criticism of anyone doing
this — it's the natural starting point. It's also exactly the moment to put
a charter in place, before informal usage scales into a real exposure
across the org.

## Why a charter is required
Left ad hoc, individual employees will paste whatever's convenient into
whatever AI tool is open. A charter is the enterprise's explicit answer to:
what may be typed where, and under what settings. Without it, the default
assumptions (a consumer account's defaults) are usually the wrong ones for
confidential company data.

## The toggles that must be explicitly turned off
Most consumer/team AI plans ship with these **on by default** — they need
to be found and turned off, not assumed:
- **Model training on your content** — many consumer-tier plans allow the
  vendor to use conversation content to improve future models unless you
  opt out.
- **Indefinite/long retention** — chat history is often kept far longer
  than a session, and searchable by the account holder or admin.
- Both of these are settings, not personality traits of the tool — check
  them for whatever plan HT actually uses before assuming either is off.

## Subscriptions vs. API — the quota reality
- Consumer/team chat subscriptions (the kind most people use day to day)
  come with **usage quotas** — heavy users learn quickly that a normal
  workday can burn through a daily/weekly limit faster than expected.
- **True zero-data-retention (ZDR)** — a contractual guarantee the vendor
  doesn't retain your data at all, not just "doesn't train on it" — is
  generally an **API-tier arrangement**: no fixed quota in the same sense,
  pay-per-use, but it costs more and it is **not automatically granted** —
  it typically requires a specific commercial agreement with the vendor,
  and exists in some vendors' terms "on paper" more than as something every
  customer actually gets by default. Don't assume ZDR because a sales page
  mentions it — confirm it's actually contracted for the account in use.

## What this means practically for HT, starting now
- **Short term (this week):** a one-page written guideline — even
  informal — beats no guideline. State plainly: no customer/financial data
  in personal AI accounts; anything sensitive waits for a team/business-
  tier account with training and retention toggled off.
- **Near term:** move to a company-owned team/business-tier plan (rather
  than everyone on personal accounts) — this is what makes the toggles
  above something IT/ops can actually verify, instead of trusting each
  individual's settings.
- **If/when a specific project needs contractual zero-retention**, that's a
  procurement conversation (API access, a signed agreement) — flag it
  early, don't assume any chat app already provides it by default.
- See `CONTRACT.md` (root) and `templates/atlas/CONTRACT.template.md` for
  how this gets written into a specific project's contract once HT has
  something to point to.

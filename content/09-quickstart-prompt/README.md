# The quickstart prompt

The close of the session, and the actual point of the whole talk: everyone
leaves with one thing they can paste into an AI chat *today*, for whatever
they're working on — not just a version of this presentation.

## What to say on stage
"You don't need to remember any of the ATLAS detail. You need one prompt."

## The prompt (say it, show it, let people photograph the slide)

> I want to start a new project for **[describe your goal — anything, not
> a presentation]**. Look at helloai.atarigo.net/bootstrap and set it up
> accordingly.

This relies on the assistant being able to fetch the page — true by
default for claude.ai and Claude Code. `helloai.atarigo.net/bootstrap`
exists specifically to be fetched and acted on directly: plain, direct
instructions (read the templates, draft a Mandate, then a Contract, then
State) rather than a slide deck to parse. There's also a plain-text
`/llms.txt` at the site root — the same idea as the emerging `llms.txt`
web convention some sites now publish for AI crawlers; this repo dogfoods
it.

## Fallback prompt — if an assistant can't browse the web
Some setups (an API call with no tools, a locked-down chat) can't fetch
external pages. In that case, spell it out:

> I want to start a new project for **[your goal]**. Set it up using the
> ATLAS framework — Mandate, then Contract, then a living State file,
> Sprints optional. Use the worked examples at
> github.com/Siroccomeister/hello-ai/tree/main/templates/atlas as a model
> for the shape and level of detail — not the content. Draft the Mandate
> with me first, then the Contract, before we do any actual work.

## Why the short version works
- **`/bootstrap` is written *to* the assistant**, not to a human — plain
  numbered steps, no slide framing, no styling to parse around.
- **It still points back to the full templates repo**, so the assistant
  isn't guessing at what "ATLAS" means — it goes and reads the real worked
  example before drafting anything.
- **The goal is deliberately left open** — field ops workflow, a personal
  project, a software feature, a marketing campaign, anything.

## What "done" looks like for this closing moment
Someone in the room opens their phone or laptop, pastes the short prompt
with their own real goal filled in, and has a Mandate drafted before they
leave the room.

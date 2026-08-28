<!--
  ILLUSTRATIVE EXAMPLE — replace this content with your own project.
  Keep the section headings and the level of specificity, not the words.
-->
# Mandate — Field-Report Assistant

## Why this exists
Field agents write up visit notes in inconsistent formats, and someone on
the ops team currently spends ~3 hours a week reformatting them into the
standard weekly report. We want an AI-assisted workflow that takes raw
field notes and produces a correctly-formatted draft report, so that hour
goes back to the ops team and reports go out same-day instead of two days
later.

## Audience / stakeholders
Field agents (input), ops team lead (owns the report format and signs off
before anything is sent out), regional manager (consumes the final report).
No customer or loan-specific data leaves internal tools at any point.

## What "done" looks like
- A field agent can paste rough notes into the assistant and get a
  correctly-formatted draft in under a minute.
- The ops lead reviews and approves in under 5 minutes, down from ~45.
- Reports go out same-day for at least 80% of weeks, measured over a month.

## Non-goals
- This does not decide report *content* or make judgment calls on what to
  flag — it formats and drafts, a human approves every report before it's
  sent.
- Not building a general note-taking app — input stays plain text/voice
  transcript, no new field-side tooling.

## Owner
Ops team lead — accountable for this mandate staying current and for
sign-off on every report before it goes out.

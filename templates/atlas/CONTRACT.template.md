<!--
  ILLUSTRATIVE EXAMPLE — replace this content with your own project.
  Keep the section headings and the level of specificity, not the words.
-->
# Contract — Field-Report Assistant

## Data sensitivity
Field notes may mention specific farmers/customers by name. That makes
this internal-tier data, not public-tier: fine inside our AI workspace
account (training/retention toggles off — see below), never in a personal
or free-tier AI account.

## Tools & MCP servers in scope
| Tool / server | What it can access | Approved for | Notes |
|---|---|---|---|
| Team AI workspace (Project) | The report-format instructions + this week's pasted notes only | Ops lead, field agents drafting | No connector attached — notes are pasted in, not pulled from a live system |
| Shared Drive folder (considered, not yet approved) | Would expose the *entire* reports folder, including past customer-named reports | Not yet approved | Needs ops-lead sign-off before connecting; until then, paste notes manually |

## Things this project must never do
- Never send a report automatically without a named human approving it
  first.
- Never connect a data source that exposes more than this week's notes
  without an explicit sign-off (see table above).
- Never use a personal/free-tier AI account for this — team workspace only.

## Approval gates
- Connecting any new data source (e.g. the Drive folder above).
- Sending a report externally (customer-facing or above the regional
  manager).

## Enterprise AI charter — applies to every tool used here
- Training-use and long-term retention toggles are off in our workspace
  account settings — checked, not assumed, each time a new seat is added.
- If genuine zero-data-retention were ever required for this project, that
  is an API-tier arrangement (cost + contract), not something the standard
  chat subscription grants by default.

## Reference policies
HT's internal data-handling policy (link once confirmed) governs anything
this contract doesn't explicitly cover.

# AI Architecture Portfolio

This repository captures the architecture of an AI application as it develops
from an initial problem framing through implementation choices to a final
capstone design.

## Scenario and assumptions

The specific business scenario, users, requirements, and constraints have not
been defined yet. The documents in this repository are a working record, not a
claim that a production system already exists. Replace the prompts and
assumptions in each session document with the decisions and evidence from the
course.

Until the scenario is chosen, use these working assumptions:

- The system will include an AI/ML capability, but its purpose and model are
  undecided.
- Requirements, scale, data sensitivity, deployment environment, and
  operational constraints must be recorded before selecting an architecture.
- Decisions in `adr/` remain proposed until their status is changed and their
  rationale is supported by the scenario.

## How to read this repository

1. Start with the session notes in `docs/` to follow the design from framing
   through the building blocks.
2. Check `diagrams/` for architecture visuals and their editable source files.
3. Read `adr/` for decisions, alternatives, and consequences.
4. Review `capstone/` for the consolidated final architecture and presentation.

Keep one numbered Markdown file per course session in `docs/`. Update diagrams
and decision records as the design evolves, and make the capstone consistent
with the accepted decisions.

## Repository layout

```text
README.md
docs/
  01-framing.md
  02-building-blocks.md
diagrams/
adr/
  0001-model-hosting.md
capstone/
```

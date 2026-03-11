# Machine Work Index

An open index of difficult local-machine workflows, approval boundaries, and end states.

This repository is for tasks that currently live across:

- shell history
- sticky notes
- half-remembered runbooks
- admin prompts
- browser tabs
- human babysitting

The point is simple:

- collect real local workflows with real pain
- describe where the danger points and approval boundaries are
- make it easier to discuss machine work without reducing it to slogans

This repo is intentionally broader than any single product surface.

`Klava` is one implementation path, not the definition of the index.

## What belongs here

- developer environment repair
- workstation recovery and setup
- risky migrations on a local machine
- internal IT flows with approvals
- consultant workflows that repeat across customer machines
- tasks that are too stateful or too risky for a plain chat reply

## What does not belong here

- vague "AI should automate this somehow" ideas
- tasks that require private credentials or secret data in public
- pure cloud-only workflows with no meaningful local machine surface

## Submit a case note

- Open an issue: https://github.com/junior2wnw/machine-work-index/issues/new?template=case_note.md

## Evaluation rubric

The strongest submissions usually have:

- high repetition
- real risk
- multiple steps
- ugly handoffs
- obvious approval points
- a clear end state

## Current sponsor implementation

The current public implementation path is:

- `Klava`: https://github.com/junior2wnw/klava-bot

Klava is a local-first desktop agent project with guarded terminal work, approvals, task history, and multi-step operations.

## Ground rule

No hype without specifics.

Describe the machine, the pain, the risk, and the desired end state.

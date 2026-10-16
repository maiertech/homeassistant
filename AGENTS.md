# AGENTS.md

This repository contains configuration files for my Home Assistant (HA)
instance, which you cannot access. As an agent you will never deploy anthing in
this repository to home assistant. The user will deploy automations by copying
them to the Home Assistant server and create any required resources using the
instructions in the relevant Markdown documentation.

## Docs

Use the official Home Assistant documentation for details about its behavior and
configuration: https://www.home-assistant.io/docs/.

## Verification

After changing anything in this repository, run `pnpm verify`. Resolve any
failures before considering the work complete.

## Writing style

- Capitalize only the first word in a heading.

## Issue tracker

When working with GitHub issues in `maiertech/homeassistant`, use the `gh` CLI
and follow `docs/agents/issue-tracker.md`.

## Triage labels

When applying triage labels, follow the default five-role vocabulary in
`docs/agents/triage-labels.md`; each label name matches its role.

## Domain docs

When documenting domain terminology or decisions, follow
`docs/agents/domain.md`: keep one `GLOSSARY.md` and put ADRs in the root
`docs/adr/` directory.

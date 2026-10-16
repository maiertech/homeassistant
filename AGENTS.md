# AGENTS.md

This repository contains configuration for my Home Assistant (HA) instance. You
cannot access the instance; I will provide instance-specific information and
apply configurations there.

Home Assistant documentation: https://www.home-assistant.io/docs/.

## Automations

Store automations in the `automations/` folder. When an automation needs an
entity ID, use a clearly named placeholder and ask me for the actual ID. Provide
the completed YAML for me to copy into Home Assistant.

If an automation requires a helper that I must create in Home Assistant, provide
detailed, step-by-step instructions for creating it. Assume the Home Assistant
UI is in English.

## Writing style

- Capitalize only the first word in a heading.

## Agent skills

### Issue tracker

GitHub Issues in `maiertech/homeassistant`, managed with the `gh` CLI. See `docs/agents/issue-tracker.md`.

### Triage labels

Default five-role vocabulary, with label names equal to role names. See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: one `GLOSSARY.md` and `docs/adr/` at the repo root. See `docs/agents/domain.md`.

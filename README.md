# Home Assistant

My Home Assistant automations are in `automations/`. UI helpers required by
those automations are documented individually in `helpers/`. Reusable automation
blueprints are in `blueprints/`, with the values for each instance documented in
the blueprint's comments. Domain terms are defined in `GLOSSARY.md`.

## Setup

Install the dependencies from the repository root:

```sh
pnpm install
```

This also installs the Git hooks through `husky`. Before committing, check the
whole repository with:

```sh
pnpm verify
```

The pre-commit hook checks only staged files: Prettier on Markdown and YAML, and
ESLint on YAML. The pre-push hook runs `pnpm verify`.

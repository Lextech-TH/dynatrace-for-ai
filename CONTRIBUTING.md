# Contributing

## Skill Content Is Read-Only

Skill content under `skills/` is **maintained internally at Dynatrace** and
published to this repository periodically. Every publish cycle overwrites the
`skills/` directory entirely, so **pull requests that modify files under
`skills/` will not be accepted** — the changes would be lost on the next
publish.

If you want to suggest improvements to a skill, please **open an issue**
instead. The Dynatrace team will pick it up and apply the change at the source.

## What You Can Contribute

The following files live exclusively in this repository and welcome PRs:

- `README.md`, `CONTRIBUTING.md`, `llms.txt`
- `prompts/**` — reusable prompt templates
- `plugins/**` — plugin manifests and agent configurations
- `tests/**` — CI test scripts
- `.github/**` — GitHub Actions workflows

## Reporting Issues

To report bugs, suggest new skills, or request improvements to existing skill
content, please [open a GitHub issue](../../issues/new).

## License

All contributions are licensed under Apache-2.0.

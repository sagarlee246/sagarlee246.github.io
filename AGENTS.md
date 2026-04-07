# Agent Guidelines for al-folio

A simple, clean, and responsive Jekyll theme for academics.

Use this file as a navigation hub. For technical details, use `.github/copilot-instructions.md` as the primary source of truth.

## Quick Links by Role

- **Are you a coding agent?** → Read [`.github/copilot-instructions.md`](.github/copilot-instructions.md) first (tech stack, build, CI/CD, common pitfalls & solutions)
- **Customizing the site?** → See [`.github/agents/customize.agent.md`](.github/agents/customize.agent.md)
- **Writing documentation?** → See [`.github/agents/docs.agent.md`](.github/agents/docs.agent.md)
- **Need setup/deployment help?** → [INSTALL.md](INSTALL.md)
- **Troubleshooting & FAQ?** → [TROUBLESHOOTING.md](TROUBLESHOOTING.md)
- **Customization & theming?** → [CUSTOMIZE.md](CUSTOMIZE.md)
- **Quick 5-min start?** → [QUICKSTART.md](QUICKSTART.md)

## Source of Truth

When guidance overlaps, prioritize these references in order:

1. [`.github/copilot-instructions.md`](.github/copilot-instructions.md) — tech stack, build/test commands, CI/CD behavior, known pitfalls
2. [`.github/instructions/`](.github/instructions/) — file-type-specific editing rules via `applyTo`
3. Project docs such as [INSTALL.md](INSTALL.md), [CUSTOMIZE.md](CUSTOMIZE.md), [TROUBLESHOOTING.md](TROUBLESHOOTING.md), and [CONTRIBUTING.md](CONTRIBUTING.md)

## Build and Validation

Use these command references instead of duplicating command blocks here:

- Local development and Docker workflow:
    [`.github/copilot-instructions.md#building--local-development`](.github/copilot-instructions.md#building--local-development)
- Pre-commit checks and formatting requirements:
    [`.github/copilot-instructions.md#pre-commit-requirements`](.github/copilot-instructions.md#pre-commit-requirements)
- Common deployment/build issues and fixes:
    [`.github/copilot-instructions.md#common-pitfalls--workarounds`](.github/copilot-instructions.md#common-pitfalls--workarounds)
- Expanded troubleshooting catalog:
    [TROUBLESHOOTING.md](TROUBLESHOOTING.md)

## Project Boundaries

- Site-wide config and feature flags: `_config.yml`, `_data/*.yml`
- Content collections: `_posts/`, `_pages/`, `_projects/`, `_news/`, `_books/`, `_teachings/`
- UI templates: `_layouts/`, `_includes/`
- Styling and scripts: `_sass/`, `_scripts/`
- Publications: `_bibliography/papers.bib`

For details and conventions, see:

- [README.md](README.md)
- [CUSTOMIZE.md](CUSTOMIZE.md)
- [`.github/copilot-instructions.md#project-layout--key-files`](.github/copilot-instructions.md#project-layout--key-files)

## Development Workflow

For commit message format and git practices, see [`.github/GIT_WORKFLOW.md`](.github/GIT_WORKFLOW.md).

Use file-scoped instructions for edits:

| File Type                                     | Instruction File                                                                                |
| --------------------------------------------- | ----------------------------------------------------------------------------------------------- |
| Markdown content (`_posts/`, `_pages/`, etc.) | [markdown-content.instructions.md](.github/instructions/markdown-content.instructions.md)       |
| YAML config (`_config.yml`, `_data/`)         | [yaml-configuration.instructions.md](.github/instructions/yaml-configuration.instructions.md)   |
| BibTeX (`_bibliography/`)                     | [bibtex-bibliography.instructions.md](.github/instructions/bibtex-bibliography.instructions.md) |
| Liquid templates (`_includes/`, `_layouts/`)  | [liquid-templates.instructions.md](.github/instructions/liquid-templates.instructions.md)       |
| JavaScript (`_scripts/`)                      | [javascript-scripts.instructions.md](.github/instructions/javascript-scripts.instructions.md)   |

## Documentation Map

- Setup and deployment: [INSTALL.md](INSTALL.md)
- Theme and feature customization: [CUSTOMIZE.md](CUSTOMIZE.md)
- Common issues and fixes: [TROUBLESHOOTING.md](TROUBLESHOOTING.md)
- Contribution process: [CONTRIBUTING.md](CONTRIBUTING.md)
- SEO configuration: [SEO.md](SEO.md)
- Analytics options: [ANALYTICS.md](ANALYTICS.md)
- FAQ: [FAQ.md](FAQ.md)

For issue history and edge cases, also see [GitHub Issues](https://github.com/alshedivat/al-folio/issues).

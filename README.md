# RNC Solutions Group · GitHub defaults

This public repository maintains the [RNC Solutions Group organization profile](profile/README.md) and reusable GitHub community standards.

## Repository contents

| Path | Purpose | Inherited by other repositories? |
| --- | --- | --- |
| [`profile/README.md`](profile/README.md) | Public organization profile. | No; appears on the organization profile. |
| [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE/) | Shared bug, feature, and development-task issue forms. | Yes, when a repository has no issue template or issue-template configuration of its own. |
| [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) | Default pull request description. | Yes, unless overridden by that repository. |
| [`CONTRIBUTING.md`](CONTRIBUTING.md) | Default contribution guidance. | Yes, unless overridden by that repository. |
| [`templates/REPOSITORY_README.md`](templates/REPOSITORY_README.md) | Starter README to adapt for each project. | No; copy and customize it explicitly. |

## Using these defaults

1. Start with the repository README starter and remove sections that do not apply.
2. Let GitHub provide the shared issue forms and pull request template by default.
3. Override a default locally when a repository's needs differ.
4. Keep project-specific setup, CI checks, release instructions, security reporting, and licenses in the individual repository.

**Important:** If a repository defines *any* valid issue template or an issue-template `config.yml` of its own, GitHub does not mix in the default issue forms from this repository. Copy the forms you still want when customizing that chooser.

These files are starting points, not proof of branch protections or required checks. Configure branch rules, reviewer requirements, and CI per repository. Licenses also belong to individual repositories; no blanket open-source license is implied by this profile or these templates.

## Updating the defaults

Propose changes on a feature branch and open a pull request for review. Changes merged into the default branch may affect issue and PR creation across repositories that inherit these files.

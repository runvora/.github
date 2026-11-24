# Runvora `.github`

This repository holds the organization-wide defaults and public profile for the Runvora GitHub organization.

## Contents

| Path | Purpose |
| --- | --- |
| `profile/README.md` | Public organization profile shown on the Runvora GitHub page. |
| `AGENTS.md` | Organization-wide agent protocol: shared engineering principles for AI coding agents. |
| `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md`, `SUPPORT.md` | Default community health files. |
| `ISSUE_TEMPLATE/` | Default issue templates and issue chooser configuration. |
| `PULL_REQUEST_TEMPLATE.md` | Default pull request template. |
| `assets/branding/` | Placeholder for future brand assets and branding direction. |
| `.github/copilot-instructions.md` | Points GitHub Copilot to `AGENTS.md`. |

## Default community health files

GitHub applies these files to organization repositories that do not define their own. Repositories that contain their own version of a file use theirs instead.

## Adopting the agent protocol

GitHub does not automatically propagate `AGENTS.md` to other repositories. Each Runvora repository must explicitly adopt the central protocol, either by:

- referencing the organization-wide [`AGENTS.md`](AGENTS.md) from its own repository-local `AGENTS.md` and `.github/copilot-instructions.md`, or
- using a verified synchronization mechanism.

Repository-local instructions may add context and refine practices, but must not weaken the security requirements in this protocol.

## Status

Runvora is in early development. Architecture, licensing, and repository boundaries are still being evaluated.

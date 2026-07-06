# Agent guide — zenlab-dev/.github

This repository controls organization-level GitHub profile content for
`zenlab-dev`.

## Repo model

- `profile/README.md` is the public organization profile shown on GitHub.
- There is no build step, package manager, runtime app, or deployment workflow.

## Rules of the road

- Keep this repo public-safe. Do not add private infrastructure details,
  secrets, tokens, internal hostnames, or private SSH material.
- Keep wording concise and personal-homelab oriented. This is an organization
  profile, not a product landing page.
- Prefer small Markdown-only changes. If adding images or other assets, keep
  them lightweight and reference why they belong in the org profile.

## Validation

- Review rendered Markdown mentally or with a local Markdown preview.
- Run `git diff --check` before committing.


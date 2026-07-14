# Open Source Challenges: Dynatrace Community Edition

This repo hosts a curated selection of challenges from [off-on-dev/open-source-challenges](https://github.com/off-on-dev/open-source-challenges), adapted for the [Dynatrace community](https://community.dynatrace.com/).

## Why this repo exists

The OffOn open source challenges are designed to run in a devcontainer, both locally and via GitHub Codespaces. To give the Dynatrace community dedicated usage tracking, each challenge run needs to report where it came from.

Rather than adding Dynatrace-specific devcontainer configs into the core OffOn repo, which would clutter a partner-agnostic project with community-specific setup, we maintain this separate repo. It contains the subset of challenges relevant to the Dynatrace community, with its own devcontainer configuration.

## Staying in sync with OffOn

Challenge content in this repo is sourced from the upstream OffOn repo and should not diverge. Please make content fixes upstream in [off-on-dev/open-source-challenges](https://github.com/off-on-dev/open-source-challenges) rather than here. This repo only adds the devcontainer configuration on top.

Sync process:
- **Currently:** manual. Selected challenges are copied over from upstream as needed.
- **Planned:** a manually-triggered GitHub Actions workflow that opens a PR with upstream updates, so maintainers can pick exactly which challenges get synced rather than pulling in everything automatically.

## Attribution

Challenge content originates from [off-on-dev/open-source-challenges](https://github.com/off-on-dev/open-source-challenges). See that repo for license terms.

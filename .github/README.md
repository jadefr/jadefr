# GitHub Profile Metrics

This repository is configured to generate GitHub profile metrics using the Metrics action.

## Setup

1. Create a personal access token (classic) with the `read:org` and `repo` scopes if needed.
2. In this repository, add a secret named `METRICS_TOKEN` with that token.
3. Enable GitHub Actions for the repository.
4. Run the workflow manually or wait for the scheduled run.

The workflow in [.github/workflows/metrics.yml](.github/workflows/metrics.yml) renders the metrics into your profile README.

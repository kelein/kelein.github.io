# Helm Charts

![Helm](https://img.shields.io/badge/helm_v3-%23101683.svg?style=for-the-badge&logo=helm&logoColor=white)  ![GitHub](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=for-the-badge&logo=githubactions&logoColor=white)   ![Build](https://img.shields.io/github/actions/workflow/status/kelein/charts/pages%2Fpages-build-deployment?style=for-the-badge&logo=github)

Helm Charts Library for Kubernetes, ready to launching with [Helm](https://github.com/helm/helm).

## Usage

```bash
❯ helm repo add <REPO> https://kelein.github.io/charts
"<REPO>" has been added to your repositories

❯ helm repo list
NAME        URL
"<REPO>"    https://kelein.github.io/charts

❯ helm repo update
Hang tight while we grab the latest from your chart repositories...
...Successfully got an update from the "urans" chart repository
...Successfully got an update from the "bitnami" chart repository
Update Complete. ⎈ Happy Helming! ⎈

❯ helm search repo <CHART> --versions
❯ helm -n <NS> install <REPO>/<CHART> --version <VERSION>
```

## Workflow

<img alt="workflow" width="85%" src="docs/helm-workflow.png">

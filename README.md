# .github — org-wide defaults

This special repository holds defaults that GitHub applies to **every repo** in the `exchangesolutionsinc` org that doesn't define its own:

| Path | What it does |
|---|---|
| [`profile/README.md`](profile/README.md) | The public welcome page shown at [github.com/exchangesolutionsinc](https://github.com/exchangesolutionsinc) |
| [`pull_request_template.md`](pull_request_template.md) | Default PR template for all repos (Jira key, branch naming, checklist) |
| [`workflow-templates/`](workflow-templates/) | Org-wide GitHub Actions starter templates (placeholder for now) |

## Conventions (short version)

- Default branch is **`main`** everywhere.
- Branches: `feature|bugfix|chore/<JIRA-KEY>-short-description`
- One ticket = one PR, squash merge, assign yourself, CI green before review.

Changes here affect the whole org — open a PR and tag **#devops**.

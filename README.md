# Cache Health Gate Fork PR Validation Repo

Public test repository used to validate restricted-token behavior for fork PRs.

This repo intentionally keeps one small workflow (`cache-alpha.yml`) to test:

- baseline sanity via `workflow_dispatch`
- fork PR degrade behavior via `pull_request`

No production workload.

# GitHub Actions

## Common Workflow Types

| Type | Purpose | Examples |
|------|---------|----------|
| **Validate** | Check code quality before merging | Tests, linting, static analysis (security, code quality) |
| **Build** | Produce deployable artifacts | Executables, container images |
| **Deploy** | Ship to an environment | Push-based deploys, updated tags for GitOps deploys |


![Flow diagram of a workflow](<./artifacts/flow.png>)


## Example workflow
![Hello world](<./artifacts/hello-world.png>)


## Triggering Events

Almost any github event can trigger a workflow:
* Trigger manually
* Push to branch
* Create/update pull request
* Cron jobs
* Many more

![Github Events](./artifacts/gh-events.png)


## Writing/Reusing Actions

1. Composite Action
2. Reusable Workflow
3. Js/Ts Action
4. Container Action

![Github Action types](./artifacts/actions-usage.png)
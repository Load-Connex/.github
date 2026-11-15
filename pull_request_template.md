## Jira

LX-

## What and why

<!-- What does this PR change, and why? One or two sentences is fine. -->

## How it was tested

<!-- Local run, unit tests, staging check, screenshots for UI changes. -->

## Checklist

- [ ] PR title starts with the Jira key (for example `LX-1234: short summary`)
- [ ] Builds locally and tests pass
- [ ] New config or secrets added in every environment (SSM / Secrets Manager / gitops manifests)
- [ ] Database migration: none / included and reviewed
- [ ] No new Trivy ignore without an expiry date and a Jira ticket
- [ ] No secrets, keys or connection strings in the code

## Deploy notes

<!-- Merge order (for example "merge gitops PR first"), breaking changes, feature flags.
     Merging to the default branch deploys to staging automatically. -->

- Risk: low / medium / high
- Rollback: <!-- revert this PR / redeploy previous image tag / other -->

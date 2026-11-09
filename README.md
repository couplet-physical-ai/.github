# couplet-physical-ai/.github

Organization-wide defaults for [couplet-physical-ai](https://github.com/couplet-physical-ai):

- `profile/README.md` — the org profile page
- `CONTRIBUTING.md` (DCO sign-off), `CODE_OF_CONDUCT.md`, `SECURITY.md` — community health defaults for every repo without its own copy
- `ISSUE_TEMPLATE/`, `PULL_REQUEST_TEMPLATE.md` — default issue and PR templates
- `.github/workflows/dco.yml` — DCO check, reusable from any repo:

```yaml
# .github/workflows/dco.yml in a project repo
name: DCO
on: pull_request
jobs:
  DCO:
    uses: couplet-physical-ai/.github/.github/workflows/dco.yml@main
```


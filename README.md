# .github

The organization-level configuration repository for [CG Homelab](https://github.com/cg-homelab). GitHub treats a repository named `.github` as the place to keep defaults that apply across the whole organization.

## The organization profile

`profile/README.md` is what renders on the [organization page](https://github.com/cg-homelab). Edit that file and push to `main` — the page updates immediately. This root `README.md` is not shown there; it only documents the repository itself.

## What else GitHub picks up from here

Nothing below exists yet, but GitHub will use it automatically if added:

- `ISSUE_TEMPLATE/` — issue forms and templates offered in repositories that have none of their own
- `PULL_REQUEST_TEMPLATE.md` — default pull request body
- `CONTRIBUTING.md`, `CODE_OF_CONDUCT.md`, `SECURITY.md` — organization defaults
- `workflow-templates/` — starter workflows offered in the Actions tab of every repository

These are defaults only. A repository that ships its own copy of any of these files uses that copy instead.

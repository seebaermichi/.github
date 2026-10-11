# .github

Default community health files for every public repository under
[seebaermichi](https://github.com/seebaermichi).

GitHub shows these files on any public repository of this account that does not
carry its own copy: the security policy, the contributing guide, the issue
templates and the pull request template. One copy here replaces one copy per
repository, so there is nothing to keep in sync.

A repository that needs something different adds its own file, which then
takes precedence for that file type only. `nera` (the generator) does this for
`CONTRIBUTING.md`, because the Nera plugin READMEs link to it.

| File | Shown as |
|---|---|
| `SECURITY.md` | the repository's **Security policy** |
| `CONTRIBUTING.md` | the contributing link on new issues and pull requests |
| `.github/ISSUE_TEMPLATE/` | the template chooser on **New issue** |
| `.github/pull_request_template.md` | the default body of a new pull request |

`FUNDING.yml` (the **Sponsor this project** box) is deliberately *not* here:
it would reach every public repository, forks included. Each Nera repository
carries its own copy in `.github/FUNDING.yml` instead.

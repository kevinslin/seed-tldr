---
id: common.gh-completion
title: Gh Completion
desc: ''
updated: 1615655543056
created: 1615655543056
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gh completion

> Generate shell completion scripts for GitHub CLI commands.
> More information: <https://cli.github.com/manual/gh_completion>.

- Display the subcommand help:

`gh completion`

- Print a completion script:

`gh completion --shell {{bash|zsh|fish|powershell}}`

- Append the `gh` completion script to `~/.bashrc`:

`gh completion --shell {{bash}} >> {{~/.bashrc}}`

- Append the `gh` completion script to `~/.zshrc`:

`gh completion --shell {{zsh}} >> {{~/.zshrc}}`


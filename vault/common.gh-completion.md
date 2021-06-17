---
id: common.gh-completion
title: Gh Completion
desc: ''
updated: 1623965016125
created: 1623965016125
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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


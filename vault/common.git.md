---
id: common.git
title: Git
desc: ''
updated: 1623965016129
created: 1623965016129
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# git

> Distributed version control system.
> More information: <https://git-scm.com/>.

- Check the Git version:

`git --version`

- Show general help:

`git --help`

- Show help on a Git subcommand (like `commit`, `log`, etc.):

`git help {{subcommand}}`

- Execute a Git subcommand:

`git {{subcommand}}`

- Execute a Git subcommand on a custom repository root path:

`git -C {{path/to/repo}} {{subcommand}}`

- Execute a Git subcommand with a given configuration set:

`git -c '{{config.key}}={{value}}' {{subcommand}}`


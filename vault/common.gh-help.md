---
id: common.gh-help
title: Gh Help
desc: ''
updated: 1642441815020
created: 1642441815020
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gh help

> Display help about the GitHub CLI command.
> More information: <https://cli.github.com/manual/gh_help>.

- Display general help:

`gh help`

- Display help for the `gh help` subcommand:

`gh help --help`

- Display help about environment variables that can be used with `gh`:

`gh help environment`

- Display a markdown reference of all `gh` commands:

`gh help reference`

- Display help about formatting JSON output from `gh` using `jq`:

`gh help formatting`

- Display help about using `gh` with MinTTY:

`gh help mintty`

- Display help for a subcommand:

`gh help {{subcommand}}`

- Display help for a subcommand action:

`gh help {{pr}} {{create}}`


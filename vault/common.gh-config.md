---
id: common.gh-config
title: Gh Config
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
# gh config

> Change configuration for GitHub cli.
> More information: <https://cli.github.com/manual/gh_config>.

- Display what Git protocol is being used:

`gh config get git_protocol`

- Set protocol to SSH:

`gh config set git_protocol {{ssh}}`

- Use `delta` in side-by-side mode as the default pager for all `gh` commands:

`gh config set pager '{{delta --side-by-side}}'`

- Set text editor to Vim:

`gh config set editor {{vim}}`

- Reset to default text editor:

`gh config set editor {{""}}`

- Disable interactive prompts:

`gh config set prompt {{disabled}}`

- Set a specific configuration value:

`gh config set {{key}} {{value}}`


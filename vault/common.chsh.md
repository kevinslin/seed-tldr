---
id: common.chsh
title: Chsh
desc: ''
updated: 1642441815002
created: 1642441815002
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# chsh

> Change the user's login shell.
> More information: <https://manned.org/chsh>.

- Change the current user's login shell interactively:

`chsh`

- Change the login shell for a given user to Zsh:

`chsh --shell {{/bin/zsh}} {{username}}`

- List available shells:

`chsh --list-shells`


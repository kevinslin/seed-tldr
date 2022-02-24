---
id: linux.chsh
title: Chsh
desc: ''
updated: 1645707928412
created: 1645707928412
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

- Change the current user's login shell:

`chsh --shell {{path/to/shell}}`

- Change the login shell for a given user:

`chsh --shell {{path/to/shell}} {{username}}`

- List available shells:

`chsh --list-shells`


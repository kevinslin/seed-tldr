---
id: common.gopass
title: Gopass
desc: ''
updated: 1623965016130
created: 1623965016130
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# gopass

> Standard Unix Password Manager for Teams. Written in Go.
> More information: <https://www.gopass.pw>.

- Initialise the configuration settings:

`gopass init`

- Create a new entry:

`gopass new`

- Show all stores:

`gopass mounts`

- Mount a shared Git store:

`gopass mounts add {{store_name}} {{git_repo_url}}`

- Search interactively using a keyword:

`gopass show {{keyword}}`

- Search using a keyword:

`gopass find {{keyword}}`

- Sync all mounted stores:

`gopass sync`

- Show a particular password entry:

`gopass {{store_name|path/to/directory|email@email.com}}`


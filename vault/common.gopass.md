---
id: common.gopass
title: Gopass
desc: ''
updated: 1615655543061
created: 1615655543061
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
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


---
id: common.gibo
title: Gibo
desc: ''
updated: 1615655543057
created: 1615655543057
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# gibo

> Fetch gitignore boilerplates.
> More information: <https://github.com/simonwhitaker/gibo>.

- List available boilerplates:

`gibo list`

- Write a boilerplate to stdout:

`gibo dump {{boilerplate}}`

- Write a boilerplate to .gitignore:

`gibo dump {{boilerplate}} >>{{.gitignore}}`

- Search for boilerplates containing a given string:

`gibo search {{string}}`

- Update available local boilerplates:

`gibo update`


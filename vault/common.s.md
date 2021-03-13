---
id: common.s
title: S
desc: ''
updated: 1615655543083
created: 1615655543083
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# s

> Web search from the terminal.

- Search for a query on Google(default provider):

`s {{query}}`

- List all providers:

`s --list-providers`

- Search for a query with a given provider:

`s --provider {{provider}} {{query}}`

- Use a specified binary to perform the search query:

`s --binary "{{binary}} {{arguments}}" {{query}}`


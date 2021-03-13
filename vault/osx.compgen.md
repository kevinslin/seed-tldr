---
id: osx.compgen
title: Compgen
desc: ''
updated: 1615655543113
created: 1615655543113
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# compgen

> A built-in command for auto-completion in bash, which is called on pressing TAB key twice.

- List all commands that you could run:

`compgen -c`

- List all aliases:

`compgen -a`

- List all functions that you could run:

`compgen -A function`

- Show shell reserved key words:

`compgen -k`

- See all available commands/aliases starting with 'ls':

`compgen -ac {{ls}}`


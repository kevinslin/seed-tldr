---
id: osx.rubocop
title: Rubocop
desc: ''
updated: 1615655543115
created: 1615655543115
gitDirPath: pages/common
sources:
  - name: ''
    url: 'https://github.com/salesforce/policy_sentry'
    license: MIT
---
# rubocop

> Lint Ruby files.

- Check all files in the current directory (including subdirectories):

`rubocop`

- Check one or more specific files or directories:

`rubocop {{path/to/file}} {{path/to/directory}}`

- Write output to file:

`rubocop --out {{path/to/file}}`

- View list of cops (linter rules):

`rubocop --show-cops`

- Exclude a cop:

`rubocop --except {{cop_1}} {{cop_2}}`

- Run only specified cops:

`rubocop --only {{cop_1}} {{cop_2}}`

- Auto-correct files (experimental):

`rubocop --auto-correct`


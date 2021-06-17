---
id: osx.rubocop
title: Rubocop
desc: ''
updated: 1623965306235
created: 1623965306235
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
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


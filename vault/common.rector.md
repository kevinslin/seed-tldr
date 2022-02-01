---
id: common.rector
title: Rector
desc: ''
updated: 1642441815065
created: 1642441815065
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# rector

> An automated tool for updating and refactoring PHP 5.3+ code.
> More information: <https://github.com/rectorphp/rector>.

- Process a specific directory:

`rector process {{path/to/directory}}`

- Process a directory without applying changes (dry run):

`rector process {{path/to/directory}} --dry-run`

- Process a directory and apply coding standards:

`rector process {{path/to/directory}} --with-style`

- Display a list of available levels:

`rector levels`

- Process a directory with a specific level:

`rector process {{path/to/directory}} --level {{level_name}}`


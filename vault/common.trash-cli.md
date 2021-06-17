---
id: common.trash-cli
title: Trash CLI
desc: ''
updated: 1623965306214
created: 1623965306214
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trash-cli

> A command-line interface to the trashcan APIs.
> More information: <https://github.com/andreafrancia/trash-cli>.

- Trash files and directories:

`trash-put {{filename}}`

- Empty the trashcan:

`trash-empty`

- List trashed files:

`trash-list`

- Restore a trashed file by choosing a number from the list that results from this command:

`trash-restore`

- Remove individual files from the trashcan:

`trash-rm {{filename}}`


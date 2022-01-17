---
id: linux.trash
title: Trash
desc: ''
updated: 1642441815115
created: 1642441815115
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# trash

> A CLI for managing the trashcan / recycling bin.
> More information: <https://github.com/andreafrancia/trash-cli>.

- Delete a file and send it to the trash:

`trash {{path/to/file}}`

- List all files in the trash:

`trash-list`

- Interactively restore a file from the trash:

`trash-restore`

- Empty the trash:

`trash-empty`

- Permanentely delete all files in the trash which are older than 10 days:

`trash-empty {{10}}`

- Remove all files in the trash, which match a specific blob pattern:

`trash-rm "{{*.o}}"`

- Remove all files with a specific original location:

`trash-rm {{/path/to/file_or_directory}}`


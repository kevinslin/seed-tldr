---
id: linux.readpe
title: Readpe
desc: ''
updated: 1642441815110
created: 1642441815110
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# readpe

> Displays information about PE files.
> More information: <https://manned.org/readpe>.

- Display all information about a PE file:

`readpe {{path/to/executable}}`

- Display all the headers present in a PE file:

`readpe --all-headers {{path/to/executable}}`

- Display all the sections present in a PE file:

`readpe --all-sections {{path/to/executable}}`

- Display a specific header from a PE file:

`readpe --header {{dos|coff|optional}} {{path/to/executable}}`

- List all imported functions:

`readpe --imports {{path/to/executable}}`

- List all exported functions:

`readpe --exports {{path/to/executable}}`


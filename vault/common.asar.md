---
id: common.asar
title: Asar
desc: ''
updated: 1623965306174
created: 1623965306174
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# asar

> A file archiver for the Electron platform.
> More information: <https://github.com/electron/asar>.

- Archive a file or directory:

`asar pack {{path/to/file_or_directory}} {{archived.asar}}`

- Extract an archive:

`asar extract {{archived.asar}}`

- Extract a specific file from an archive:

`asar extract-file {{archived.asar}} {{file}}`

- List the contents of an archive file:

`asar list {{archived.asar}}`


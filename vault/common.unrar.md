---
id: common.unrar
title: Unrar
desc: ''
updated: 1623965016154
created: 1623965016154
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# unrar

> Extract RAR archives.

- Extract files with original directory structure:

`unrar x {{compressed.rar}}`

- Extract files to a specified path with the original directory structure:

`unrar x {{compressed.rar}} {{path/to/extract}}`

- Extract files into current directory, losing directory structure in the archive:

`unrar e {{compressed.rar}}`

- Test integrity of each file inside the archive file:

`unrar t {{compressed.rar}}`

- List files inside the archive file without decompressing it:

`unrar l {{compressed.rar}}`


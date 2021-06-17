---
id: common.unar
title: Unar
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
# unar

> Extract contents from archive files.

- Extract an archive to the current directory:

`unar {{archive}}`

- Extract an archive to the specified directory:

`unar -o {{path/to/directory}} {{archive}}`

- Force overwrite if files to be unpacked already exist:

`unar -f {{archive}}`

- Force rename if files to be unpacked already exist:

`unar -r {{archive}}`

- Force skip if files to be unpacked already exist:

`unar -s {{archive}}`


---
id: common.objdump
title: Objdump
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# objdump

> View information about object files.

- Display the file header information:

`objdump -f {{binary}}`

- Display the dis-assembled output of executable sections:

`objdump -d {{binary}}`

- Display a complete binary hex dump of all sections:

`objdump -s {{binary}}`


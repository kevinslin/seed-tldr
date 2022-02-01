---
id: common.objdump
title: Objdump
desc: ''
updated: 1642441815052
created: 1642441815052
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# objdump

> View information about object files.
> More information: <https://manned.org/objdump>.

- Display the file header information:

`objdump -f {{binary}}`

- Display the dis-assembled output of executable sections:

`objdump -d {{binary}}`

- Display a complete binary hex dump of all sections:

`objdump -s {{binary}}`


---
id: linux.modinfo
title: Modinfo
desc: ''
updated: 1623965016165
created: 1623965016165
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# modinfo

> Extract information about a Linux kernel module.

- List all attributes of a kernel module:

`modinfo {{kernel_module}}`

- List the specified attribute only:

`modinfo -F {{author|description|license|parm|filename}} {{kernel_module}}`


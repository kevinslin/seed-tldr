---
id: linux.fc-list
title: Fc List
desc: ''
updated: 1623965306222
created: 1623965306222
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# fc-list

> List available fonts installed on the system.

- Return a list of installed fonts in your system:

`fc-list`

- Return a list of installed fonts with given name:

`fc-list | grep '{{DejaVu Serif}}'`

- Return the number of installed fonts in your system:

`fc-list | wc -l`


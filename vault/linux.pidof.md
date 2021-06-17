---
id: linux.pidof
title: Pidof
desc: ''
updated: 1623965306227
created: 1623965306227
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pidof

> Gets the ID of a process using its name.

- List all process IDs with given name:

`pidof {{bash}}`

- List a single process ID with given name:

`pidof -s {{bash}}`

- List process IDs including scripts with given name:

`pidof -x {{script.py}}`

- Kill all processes with given name:

`kill "$(pidof {{name}})" `


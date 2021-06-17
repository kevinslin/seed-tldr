---
id: linux.prt-get
title: Prt Get
desc: ''
updated: 1623965016167
created: 1623965016167
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# prt-get

> The CRUX package manager.

- Install a package:

`prt-get install {{package_name}}`

- Install a package with dependency handling:

`prt-get depinst {{package_name}}`

- Update a package manually:

`prt-get upgrade {{package_name}}`

- Remove a package:

`prt-get remove {{package_name}}`

- Upgrade the system from the local ports tree:

`prt-get sysup`

- Search the ports tree:

`prt-get search {{package_name}}`

- Search for a file in a package:

`prt-get fsearch {{file}}`


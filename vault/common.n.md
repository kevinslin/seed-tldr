---
id: common.n
title: 'N'
desc: ''
updated: 1646143303304
created: 1646143303304
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# n

> Tool to manage multiple node versions.
> More information: <https://github.com/tj/n>.

- Install a given version of node. If the version is already installed, it will be activated:

`n {{version}}`

- Display installed versions and interactively activate one of them:

`n`

- Remove a version:

`n rm {{version}}`

- Execute a file with a given version:

`n use {{version}} {{file.js}}`

- Output binary path for a version:

`n bin {{version}}`


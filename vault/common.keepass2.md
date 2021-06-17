---
id: common.keepass2
title: Keepass2
desc: ''
updated: 1623965306194
created: 1623965306194
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# keepass2

> A light-weight password manager.
> More information: <https://keepass.info>.

- Start KeePass 2, opening the most recently-opened password database:

`keepass2`

- Start KeePass 2, opening a specific password database:

`keepass2 {{path/to/database.kbdx}}`

- Use a specific key file to open a password database:

`keepass2 {{path/to/database.kbdx}} -keyfile:{{path/to/key/file.key}}`


---
id: linux.compose
title: Compose
desc: ''
updated: 1623965306220
created: 1623965306220
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# compose

> An alias to a `run-mailcap`'s action compose.
> Originally `run-mailcap` is used to mime-type/file.

- Compose action can be used to compose any existing file or new on default mailcap edit tool:

`compose {{filename}}`

- With `run-mailcap`:

`run-mailcap --action=compose {{filename}}`


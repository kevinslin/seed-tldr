---
id: common.pnpx
title: Pnpx
desc: ''
updated: 1623965016145
created: 1623965016145
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# pnpx

> Directly execute binaries from npm packages, using `pnpm` instead of `npm`.
> More information: <https://pnpm.io/pnpx-cli>.

- Execute the binary from a given npm module:

`pnpx {{module_name}}`

- Execute a specific binary from a given npm module, in case the module has multiple binaries:

`pnpx --package {{package_name}} {{module_name}}`

- Display help:

`pnpx --help`


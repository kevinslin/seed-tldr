---
id: common.topgrade
title: Topgrade
desc: ''
updated: 1642441815077
created: 1642441815077
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# topgrade

> Update all applications on the system.
> More information: <https://github.com/r-darwish/topgrade>.

- Run updates:

`topgrade`

- Say yes to all updates:

`topgrade -y`

- Cleanup temporary/old files:

`topgrade -c`

- Disable a certain update operation:

`topgrade --disable {{operation}}`

- Only perform a certain update operation:

`topgrade --only {{operation}}`

- Edit the config file with default editor:

`topgrade --edit-config`


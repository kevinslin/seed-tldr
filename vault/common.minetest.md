---
id: common.minetest
title: Minetest
desc: ''
updated: 1642441815047
created: 1642441815047
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# minetest

> Multiplayer infinite-world block sandbox.
> See also `minetestserver`, the server-only binary.
> More information: <https://wiki.minetest.net/Minetest>.

- Start Minetest in client mode:

`minetest`

- Start Minetest in server mode by hosting a specific world:

`minetest --server --world {{name}}`

- Write logs to a specific file:

`minetest --logfile {{path/to/file}}`

- Only write errors to the console:

`minetest --quiet`


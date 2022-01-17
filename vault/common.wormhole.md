---
id: common.wormhole
title: Wormhole
desc: ''
updated: 1642441815083
created: 1642441815083
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# wormhole

> Get things from one computer to another, safely.
> More information: <https://magic-wormhole.readthedocs.io>.

- Send a file:

`wormhole send {{path/to/file}}`

- Receive a file:

`wormhole receive {{wormhole_code}}`

- Send raw text:

`wormhole send`


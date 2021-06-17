---
id: linux.ifdown
title: Ifdown
desc: ''
updated: 1623965306223
created: 1623965306223
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ifdown

> Disable network interfaces.
> More information: <https://manned.org/ifdown>.

- Disable interface eth0:

`ifdown {{eth0}}`

- Disable all interfaces which are enabled:

`ifdown -a`


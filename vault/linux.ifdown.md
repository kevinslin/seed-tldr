---
id: linux.ifdown
title: Ifdown
desc: ''
updated: 1615663978747
created: 1615663978747
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# ifdown

> Disable network interfaces.

- Disable interface eth0:

`ifdown {{eth0}}`

- Disable all interfaces which are enabled:

`ifdown -a`


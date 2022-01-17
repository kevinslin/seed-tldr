---
id: linux.ifdown
title: Ifdown
desc: ''
updated: 1642441815097
created: 1642441815097
stub: false
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


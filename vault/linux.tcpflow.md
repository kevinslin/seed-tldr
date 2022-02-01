---
id: linux.tcpflow
title: Tcpflow
desc: ''
updated: 1642441815114
created: 1642441815114
stub: false
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# tcpflow

> Capture TCP traffic for debugging and analysis.

- Show all data on the given interface and port:

`tcpflow -c -i {{eth0}} port {{80}}`


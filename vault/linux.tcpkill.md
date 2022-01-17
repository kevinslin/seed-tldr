---
id: linux.tcpkill
title: Tcpkill
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
# tcpkill

> Kills specified in-progress TCP connections.

- Kill in-progress connections at a specified interface, host and port:

`tcpkill -i {{eth1}} host {{192.95.4.27}} and port {{2266}}`


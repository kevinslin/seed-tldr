---
id: common.traceroute
title: Traceroute
desc: ''
updated: 1623965016153
created: 1623965016153
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# traceroute

> Print the route packets trace to network host.

- Traceroute to a host:

`traceroute {{host}}`

- Disable IP address and host name mapping:

`traceroute -n {{host}}`

- Specify wait time for response:

`traceroute -w {{0.5}} {{host}}`

- Specify number of queries per hop:

`traceroute -q {{5}} {{host}}`

- Specify size in bytes of probing packet:

`traceroute {{host}} {{42}}`


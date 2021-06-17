---
id: common.openconnect
title: Openconnect
desc: ''
updated: 1623965306201
created: 1623965306201
isDir: false
gitNotePath: 'pages/{{ noteHiearchy }}.md'
sources:
  - name: tldr-pages
    url: 'https://github.com/tldr-pages/tldr/blob/master/LICENSE.md'
    license: Creative Commons
---
# openconnect

> A VPN client, for Cisco AnyConnect VPNs and others.
> More information: <https://www.infradead.org/openconnect/manual.html>.

- Connect to a server:

`openconnect {{vpn.example.org}}`

- Connect to a server, forking into the background:

`openconnect --background {{vpn.example.org}}`

- Terminate the connection that is running in the background:

`killall -SIGINT openconnect`

- Connect to a server, reading options from a config file:

`openconnect --config={{path/to/file}} {{vpn.example.org}}`

- Connect to a server and authenticate with a specific SSL client certificate:

`openconnect --certificate={{path/to/file}} {{vpn.example.org}}`

